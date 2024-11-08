# GeneC
GeneC is a low-level esoteric programming language where the code resembles the symbols used to represent strands of DNA and RNA.

It uses a quarternary numeral system to represent all data. Either the characters ACGT or ACGU are used to represent instructions and numbers, depending on the context.

Because of the languages low-level nature, there is both a data and code segment. The data segment is written in the ACGT format to represent DNA, while the code segment is written using ACGU for RNA. When dealing with numbers, they are written using ACGT because they are data.

This is how you would write numbers using the ACGT system. Note how in the examples, they are ordered similarly to big-endianness.
| Character | Number |
| A         | 0      |
| C         | 1      |
| G         | 2      |
| T-U       | 3      |
For example: AC = 4, CC = 5, GC = 6, TC = 7, AG = 8, etc

You would only use the `U` character when writing instruction codes or other code-related ops.
