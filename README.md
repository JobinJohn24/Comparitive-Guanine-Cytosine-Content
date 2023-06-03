# Comparative Analysis of Guanine-Cytosine Composition Percentage in Species

## Introduction
In this research project, I aim to compare the guanine-cytosine (GC) composition percentages between five subjects; casper Zebrafish and H37RV Mycobacterium tuberculosis, canis lupus tamiliaris (dog), mus musculus (japanese wild mouse), and homosapiens (humans) and compare the statistical analysis. The GC composition is an essential genomic characteristic that can provide insights into the genetic makeup and evolution of organisms. By comparing the GC composition percentages of these five species researchers can gain a better understanding identifying regions of genomic variation.

## Dataset Description
For my analysis, I utilized genomic sequences obtained from public databases for each of the species below:
* Canis lupus familiaris: NCBI Genome- https://www.ncbi.nlm.nih.gov/genome/?term=canis%20lupus%20familiaris
* Japanese wild mouse: NCBI Genome- https://www.ncbi.nlm.nih.gov/genome/?
* Mycobacterium Tuberculosis: TB Database- https://www.tbdb.org/
* Danio rerio: ZFIN: https://zfin.org/
* Homo sapiens: NCBI Genome: https://www.ncbi.nlm.nih.gov/genome/?term=homo%20sapiens

## Data Analysis and Visualization
### Data Preparation
To calculate the GC composition percentage, I employed computational methods to analyze the genomic sequences. I used utliization tools, Biopython and custom scripts to extract genomic sequence and calculate the . The resulting GC composition percentages were then used for further analysis and comparison.

### Data Comparison
To compare the GC composition percentages between five species, employment of statistical analysis techniques such as a t-test and ANOVA analysis was conducted. If and when the discrenpancy was every too large for variability, a post-hoc test was involved to identify the pairwise differences between species.

### Data Visualization
To present my findings, I employed various data visualization tools. I utilized Python libraries such as Matplotlib and Seaborn to create visually appealing plots. I generated bar charts, box plots, and scatter plots to illustrate the differences in the GC composition percentages between casper Zebrafish and H37RV Mycobacterium tuberculosis. These visualizations help in understanding the distribution and variation of GC composition in the two species.

[example.template.png]
Figure 1.1 represents a pie chart given the results of the t-test for species' Casper Zebrafish and H37RV Mycobacterium Tuberculosis.

[example2.template.png]
Figure 1.2 represents the results from the ANOVA statistical analysis

To present my findings, I employed various data visualization tools. I utilized Python libraries such as Matplotlib and Seaborn to create visually appealing plots. I generated bar charts, box plots, and scatter plots to illustrate the differences in the GC composition percentages between casper Zebrafish and H37RV Mycobacterium tuberculosis. These visualizations help in understanding the distribution and variation of GC composition in the two species.

## Expected Results
Based on previous studies, I anticipate observing differences in the GC composition percentages between Zebrafish and Mycobacterium tuberculosis. Zebrafish is a vertebrate organism with a relatively higher GC content compared to Mycobacterium tuberculosis, which is a bacterial pathogen known for its low GC content. I expect to see statistically variations reflecting the genomic characteristics of these two organisms.

## Instructions to Reproduce
To reproduce my analysis and visualizations, follow these steps:
1. Install Python (version X.X.X) and the required libraries listed in the `requirements.txt` file.
2. Clone the repository: `git clone https://github.com/yourusername/yourrepository.git`
3. Navigate to the project directory: `cd yourrepository`
4. Run the analysis script: `python analysis.py`
5. The results and visualizations will be generated in the specified output directory.

## Conclusion
Through my research, I aim to provide insights into the GC composition differences between Zebrafish and Mycobacterium tuberculosis. By comparing the GC percentages, I can gain a better understanding of their genetic characteristics and potential implications. These findings may contribute to the broader field of genomics and aid in future studies of these organisms.

## Work Cited
* Bian, C., Chen, W., Ruan, Z., Hu, Z., Huang, Y., Lv, Y., Xu, T., Li, J., Shi, Q., & Ge, W. (2020, March 30). Genome and Transcriptome Sequencing of casper and roy Zebrafish Mutants Provides Novel Genetic Clues for Iridophore Loss. PubMed Central (PMC). https://doi.org/10.3390/ijms21072385
* GRCz11 - danRer11 - Genome - Assembly - NCBI. (n.d.). GRCz11 - danRer11 - Genome - Assembly - NCBI. https://www.ncbi.nlm.nih.gov/assembly/GCF_000002035.6
* ASM27773v2 - Genome - Assembly - NCBI. (n.d.). ASM27773v2 - Genome - Assembly - NCBI. https://www.ncbi.nlm.nih.gov/assembly/GCF_000277735.2

