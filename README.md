# GASS-METAL

GASS-Metal is a method of searching for similar metallic sites, which uses a parallel genetic algorithm.

Here are available the templates used by the method, as well as the list of substitutions (conservative mutations).


- File Templates.zip (Templates used by GASS-Metal)

Example of a template:

3nos 1.14.13.39 Zn CYS 99 B CYS 99 A CYS 94 A CYS 94 B

Where:

3nos - PDB ID of the protein

1.14.13.39 - EC Number

Zn - Metal ion

CYS - Residue

99 - Position in the sequence

B - Chain



- File substitutions.txt (list of substitutions - conservative mutations).


Example of a substitution:


1peg, Zn, 4, CYS, HIS


Where:

1 - PDB ID of the protein

2 - Metallic ion

3 - Size of the metallic site

4 and 5 - residues that can be replaced.

