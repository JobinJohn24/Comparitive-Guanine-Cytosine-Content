# Comparative Analysis of Guanine-Cytosine Composition Percentage in Species

## Introduction
In the given research project, the objective is to conduct a comparison of guanine-cytosine (GC) composition percentages among five subjects: danio rerio (casper Zebrafish), H37RV Mycobacterium tuberculosis, canis lupus familiaris (dog), mus musculus (house mouse), & homosapiens (humans.) The intention is to perform a  statistical analysis using a one-way analysis of variance (ANOVA) approach. The guanine-cytosine composition is an essential genomic trait that can provide insights into the genetic makeup and evolution of organisms. Through comparison assessments of guanine-cytosine composition percentages across five species, researchers can gain a better understanding identifying regions of genomic variation.

## Dataset Description
For the analysis, genomic sequences were obtained from public databases for each of the species below:
* Canis Lupus Familiaris(Dog): NCBI Genome - https://www.ncbi.nlm.nih.gov/genome/?term=canis%20lupus%20familiaris
* Mus Musculus (House Mouse): NCBI Genome - https://www.ncbi.nlm.nih.gov/genome/?
* Mycobacterium Tuberculosis: TB Database - https://www.tbdb.org/
* Danio Rerio(Casper Zebrafish): ZFIN - https://zfin.org/
* Homo sapiens: NCBI Genome - https://www.ncbi.nlm.nih.gov/genome/?term=homo%20sapiens

## Data Analysis and Visualization
### Data Preparation
To calculate the guanine-cytosine composition percentage, computational methods were used to analyze the genomic sequences. I used utliization tools, Biopython and custom scripts to extract genomic sequence and understand the differences in the statistical analysis of the species. The resulting guanine-cytosine composition percentages were used for further analysis for a ANOVA analysis.

### Data Comparison
To compare the GC composition percentages between five species, employment of statistical analysis techniques such as one-way ANOVA analysis tests were conducted. If and when the discrepancy was ever too significant for variability, a post-hoc test should be involved to identify the pairwise differences between species. Below are the species represented by it's JPEG images along with their corresponding guanine-cytosine percentage content:

![table-2](https://github.com/JobinJohn24/SpeciesGC-/assets/63524391/232350f9-07a2-44a2-bed6-cfd7bd3d8bf7)

*Figure 1.1 shows the species with their corresponding guanine-cytosine percentage content.*

### Data Visualization
To present my findings, I implemented data visualization tool Seaborn to create visually appealing plots. I generated bar charts, box plots, and scatter plots to illustrate the differences in the guanine-cytosine composition percentages between five species. These visualizations help in understanding the distribution and variation of guanine-cytosine composition the given species.

![data](https://github.com/JobinJohn24/SpeciesGC-/assets/63524391/dfcd7428-56dc-41db-99e4-05ca642052e3)

*Figure 1.2 represents the distribution of guanine-cytosine content in it's genomic sequence.*


To present the findings, data visualization tool utilized was Seaborn to create visually appealing bar chart to illustrate the differences in the guanine-cytosine composition percentages between the species. These visualizations help in understanding the distribution of guanine-cytosine content in the five species, and providing the standard deviation that'll help understand the variability in the percent values in the dataset. The calculations indicated that the standard deviation measured a variability of 12.531. The percentage values helps represent the variablity in the speciesc processes and charcteristics. The guanine-cytosine content in a species is reponisble for influencing stablity of DNA, gene expression, protein coding, and moelcular or cellular processes. 

![anova](https://github.com/JobinJohn24/SpeciesGC-/assets/63524391/643aac97-c21b-4be8-a41a-93322e8b23d2)

*Figure 1.3 represents the variation in analytical results from the ANOVA test

To present the findings, the data visualization tool of Tabulate was used to create a table to compare the result of the one-way anaylsis of variance (ANOVA) test. The variation was split into three sources; between groups, within groups, and total. The variation was split into three sources to investigate the relative contributions of between and within groups. The source of variation 'Between Groups' sum of squares was 627.882, representing dissimilarities amount the groups being compared, while the source of variation 'Within Groups' had a sum of squares 0.229591, representing variability unexplained after defining the differences between the groups. The residual variability could be due to random ractors, measurement errrors, or uncontrollable factors. The degrees of freedom represent the number of independent groups or data sets considered in the analysis test.


## Expected Results
Based on the studies, It was anticipated upon observing differences in the GC composition percentages that the percentage differed greatly when considering factors such as size, . Zebrafish is a vertebrate organism with a relatively higher GC content compared to Mycobacterium tuberculosis, which is a bacterial pathogen known for its low GC content. I expect to see statistically variations reflecting the genomic characteristics of these two organisms.

## Instructions to Reproduce
To reproduce my analysis and visualizations, follow these steps:
1. Install Python (version 3.0.0) and the required libraries listed in the `requirements.txt` file.
2. Clone the repository: `git clone https://github.com/jobinjohn/SpeciesGC-.git`
3. Navigate to the project directory: `cd SpeciesGC-`
4. Run the analysis script: `python analysis.py`
5. The results and visualizations will be generated in the specified output directory.

## Conclusion
Through my research, I aim to provide insights into the GC composition differences between Zebrafish and Mycobacterium tuberculosis. By comparing the GC percentages, I can gain a better understanding of their genetic characteristics and potential implications. These findings may contribute to the broader field of genomics and aid in future studies of these organisms.

## Work Cited
* Bian, C., Chen, W., Ruan, Z., Hu, Z., Huang, Y., Lv, Y., Xu, T., Li, J., Shi, Q., & Ge, W. (2020, March 30). Genome and Transcriptome Sequencing of casper and roy Zebrafish Mutants Provides Novel Genetic Clues for Iridophore Loss. PubMed Central (PMC). https://doi.org/10.3390/ijms21072385
* GRCz11 - danRer11 - Genome - Assembly - NCBI. (n.d.). GRCz11 - danRer11 - Genome - Assembly - NCBI. https://www.ncbi.nlm.nih.gov/assembly/GCF_000002035.6
* ASM27773v2 - Genome - Assembly - NCBI. (n.d.). ASM27773v2 - Genome - Assembly - NCBI. https://www.ncbi.nlm.nih.gov/assembly/GCF_000277735.2

