**WesterLab scRNA_seq analysis**

Tools for downstream analysis of scRNA-seq differential expression data

Subroutines created by Anthony Moussa and presented in Moussa and Wester, 2022 https://doi.org/10.1101/2022.06.14.496156

**Csv files:**

**Combined_filtered_GO** - compiled DE data filtered for p-adjusted <.05 and circuit connectivity related GO terms (this file was used for all of analysis)

**CombinedAll** - compiled DE data filtered for p-adjusted <.05 but no GO filters

**DE Gene** - list of all DE genes, separated by those relevant to glutamatergic and GABAergic analysis

**Narrowed condition list** - list of conditions and what we label them as (for SFARI conditions, labels remain unchanged)

**SFARI** - list of SFARI genes and associated ASD risk

Note - the csv files needed to reproduce our analysis are listed within the Python code in "Morpheus creator testing terminal". Download the appropriate csv files and change the location in our code to the your desired folder