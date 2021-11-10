# GASS-METAL

GASS-Metal is a new method based on a parallel genetic algorithm to search for similar metal-binding sites in proteins. In addition to finding similar metal-binding sites, the method can find inter-domain sites and perform not exact matches using a substitution matrix (conservative mutations).

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

