# Pigeon-Droppings-Bacteria
Bioinformatics Analysis Pipeline 
this repository contains the reconstructed bioinformatics pipeline for analyzing microbial communities in pigeon droppings using QIIME 2 (v2023.5). The workflow includes preprocessing, quality control, taxonomic classification and visualization.

##Pipeline Steps
1. **Preprocessing and Quality Control**
   - Import raw paired end FASTQ files into QIIME2.
   - Perform denoising step using DADA2 (Divisive Amplicon Denoising Alogrithm, Version 2).
  
2. **Taxonomy Classification**
   -Taxonomic classification using a pre-trained classifier based on Greengenes 99% reference database.
   -Generate Krona plot for visualizing taxonomic composition.

3. **Outputs**
   - Feature tables
   - Taxonomic bar plots
   - Krona plots for taxonomy visualization
  
##Software and Tools 
  -**QIIME 2**- v2023.5 (https://docs.qiime2.org/2023.5).
  -**DADA2**- Integrated within QIIME 2 for quality control analysis.
  _**Greengenes Database**- used for taxonomy classification.



  

  
   
