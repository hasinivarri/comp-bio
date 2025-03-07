# comp-bio

Requirements

    Python 3.x
    requests library
    biopython (Bio module)
    naccess (for ASA calculation)

Installation

    pip install requests biopython

Ensure naccess is installed and accessible in the system.

Usage: Run the script and provide a PDB ID when prompted:

python A1_21CS10075.py

It will: Download PDB and FASTA files
Extract and compare sequences
Detect chain breaks
Compute molecular weight and ASA
Save results to A1_<PDB_ID>.txt

Output: The output file contains:

<Chain ID> <Residue Count> <Molecular Weight> <ASA Value>

Notes

    Ensure an internet connection for downloading PDB/FASTA files.
    NACCESS must be installed for ASA calculations.
