# WesterLab scRNA_seq analysis

Tools for downstream analysis of scRNA-seq differential expression data

Subroutines created by Anthony Moussa and presented in Moussa and Wester, 2022 https://doi.org/10.1101/2022.06.14.496156

### Jupyter notebook for analysis - scRNA-seq_tools.ipynb 

Includes annotated code and an organized testing terminal to run analyses

### **Csv files:**

**Combined_filtered_GO** - compiled DE data filtered for p-adjusted <.05 and circuit connectivity related GO terms (this file was used for all of analysis)

**CombinedAll** - compiled DE data filtered for p-adjusted <.05. Not filtered for GO terms

**DE Gene** - list of all DE genes, separated by those relevant to glutamatergic and GABAergic analysis

**Narrowed condition list** - list of conditions and what we label them as (for SFARI conditions, labels remain unchanged)

**SFARI** - list of SFARI genes and associated ASD risk (downloaded from 2021 SFARI Human Gene module)

### Instructions to use code for performing analysis 
The csv files needed to reproduce our analysis are listed in the Jupyter notebook under "Morpheus creator testing terminal". Download the appropriate csv files (i.e. every one except CombinedAll) and change the directory locations in our code to your desired folders. Then execute the code in the terminal and it will begin taking user inputs to perform the analysis. Save your analyzed data using the saving terminal. For matrix visualization of class-gene relationships as shown in our heatmaps, upload the Matrix csv into Morpheus by the Broad Institute and use the Meta_genes and Meta_comparison csvs to annotate the gene columns and comparison rows.
