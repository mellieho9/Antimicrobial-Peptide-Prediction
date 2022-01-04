# A machine learning model to predict antimicrobial peptides
A bioinformatics project to predict antimicrobial peptides using Pfeature, CD-HIT, and Random Forest Generation

## Background
Antimicrobial resistant are becoming a serious global health issue, as antibiotics are losing its efficacy towards treating such infections. With increasing hospitalizations and mortality rates due to antimicrobial infections, researchers have turned to antimicrobial peptides as potential alternatives to antibiotics. Antimicrobial peptides (AMPs) are small molecular peptides that play a crucial role in the living organisms' immunity against bacteria, fungi, parasites, and viruses. 

This project seeks to build a quantitative structure-activity relationship prediction model to analyse AMPs for antimicrobial drug discovery.

## Approach
In this project, I used Pfeature, a library that allows the computation of amino acids, which is essential for quantifying the molecular properties of peptides and thus providing the basis for this project's machine learning model. CD-HIT is also needed, as it allows the program to filter out redundancies in the peptide sequences and return a non-redundant subset of peptides for model-building. To install CD-HIT, I would have to install conda. For PFeature, I would have to install manually. 
For the input data, I used two datasets from the Computational Biology and Bioinformatics lab's AxPEP, which consist of antimicrobial peptides (positive set) and non-antimicrobial peptides (negative set). Such datasets have been used by the researchers at the University of Macau to create a CNN Short Antimicrobial Peptides Prediction model. 
