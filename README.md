# comp-bio

Features

Download PDB & FASTA files for a given protein ID

Extract & compare sequences from PDB and FASTA files
    
Detect mismatches and chain breaks between PDB and FASTA sequences

Compute Accessible Surface Area (ASA) using NACCESS

Estimate molecular weight of protein chains

Save analysis results in a text file

Dependencies

    Python (≥3.6)
    Biopython
    Requests
    NACCESS (external tool)

Usage

Run the script and enter a Protein ID when prompted.

Ensure NACCESS is installed and accessible in the system.

Results are saved as A1_<Protein_ID>.txt.

Example

     python computational_biophysics.py

Enter a valid PDB ID (e.g., 4HHB) when prompted.
Output

PDB & FASTA files of the given protein ID
    
Chain-wise sequence extraction & comparison
    
ASA calculations from NACCESS

Final results saved in a text file
