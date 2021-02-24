# GASS-METAL

GASS-Metal is a method of searching for similar metallic sites, which uses a parallel genetic algorithm.

Here are available the templates used by the method, as well as the list of substitutions (conservative mutations).

File Templates.zip (Templates used by GASS-Metal)

Example of a template:

3nos 1.14.13.39 Zn CYS 99 B CYS 99 A CYS 94 A CYS 94 B

1    2          3  4   5  6

Where:
1 - PDB ID of the protein
2 - EC Number
3 - Metal ion
4 - Residue
5 - Position in the sequence
6 - Chain


File substitutions.txt (list of substitutions - conservative mutations).

Example of a substitution:

1peg, Zn, 4, CYS, HIS
1     2   3   4   5

Where:
1 - PDB ID of the protein
2 - Metallic ion
3 - Size of the metallic site
4 and 5 - residues that can be replaced.
