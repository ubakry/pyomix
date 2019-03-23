# PyOmiX - Analysis Workflow
Analysis Workflow Course Project - Programming for Bioinformatics (Bioinformatics Professional Diploma)

#### LIST OF STUDENTS IN GROUP:
- Ahmed Omar Lamloum
- Moahmed Magdy AboelEla
- Usama Bakry
- Waleed Amer

#### OVERVIEW:
The overall purpose of theis program is to generate a simple phylogeny tree for multiple sequence alignments obtained from Clustal Omega, throughout a series of steps started by getting the fasta file for a list of swiss-prot ids then performing alignment through NCBI-Blastp then obtaining sequences for ids 

<p align="center" width=50% height=50%>
  <img src="https://github.com/ubakry/pyomix/blob/master/workflow.png">
</p>

#### INPUTS:
```
python pyomix.py -i <swiss-prot ids file dir> -d <database fasta file> -o <output dir>
``` 

#### OUTPUTS:
- Directory with subdirectory for each ID from the input list.
- In each directory:
    * Sequence fasta file from UniProt.
    * Alignement file from Diamond.
    * Sequences fasta file for accessions numbers from NCBI.
    * Mulitple sequence alignement file from Clustal Omega.
    * Phylogenetic tree from Clustal Omega.

#### SUBTASKS:
1. Function to make directories for swiss-prot ids. (done)
   * Input: ids file.
   * Output: list of ids directories.
2. Function to get fasta file (sequence) using request.
   * Input: swiss-prot id.
   * Output: sequence fasta file.
3. Function to align sequence using Blast.
   * Input: sequence fasta file.
   * Output: alignment file.
4. 

#### EXTERNAL MODULES AND PROGRAMMES TO BE USED:
1. NCBI Blast+ 
2. Clustal Omega (clustalo.py)
3. Simple Phylogeny Tree (simple_phylogeny.py)

#### EXPECTED DIFFICULTIES:
1. 
2. #2

#### TASKS TO BE COMPLETED BY THE 4TH OF MAY:
1. Function to make directories for swiss-prot ids. (done)
2. Function to get fasta file (sequence) using request.
3. Function to align sequence using Blast.
