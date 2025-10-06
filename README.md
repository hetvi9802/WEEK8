# Assignment 

Part A: Gene Expression Analysis 

This script analyses RNA-seq count data from the file gene_expression.tsv, which contains gene expression levels for three samples. The script reads the data, assigns gene identifiers as row names, and calculates the mean expression for each gene across samples. It outputs:
A table showing the first six genes and their expression values.
A new column (mean_expr) with the average expression per gene.
A list of the 10 most highly expressed genes.
The total number of genes with a mean expression below 10.
A histogram displaying the distribution of mean expression values across all genes.
The results help visualize expression variability and identify the most active genes.

Tree Growth Analysis 

This script analyses long-term tree growth data from growth_data.csv, which includes circumference measurements from two sites (control and treatment) over several years. The script imports the dataset, examines its column names, and calculates descriptive statistics. Specifically, it computes the mean and standard deviation of tree circumference at the start (2005) and end (2020) of the study for both sites. It then generates boxplots comparing site differences at these two time points.
Additionally, it calculates the mean 10-year growth (2010–2020) for each site and performs a two-sample t-test to determine whether the growth rates differ significantly. The outputs include:
Summary statistics (mean and SD) for each site and time point.
Two boxplots showing circumference distributions in 2005 and 2020.
Mean growth values over 10 years per site.
A t-test result with p-value indicating statistical significance.

Part B: Comparative Genomic Analysis (genomic_comparison.R)

This script compares the coding DNA sequences (CDS) of Escherichia coli K-12 MG1655 and Bifidobacteriaceae WP012. It downloads and unzips the FASTA files for both species, counts the total number of CDS, and calculates total coding DNA length. It then examines CDS length distributions through boxplots and statistical summaries (mean and median).
Further analyses include:
Nucleotide and amino acid composition using barplots to compare genomic and proteomic differences.
Codon usage and relative synonymous codon usage (RSCU) to identify preferred codons and potential translational biases.
Amino acid k-mer analysis (k = 3–5) to detect over- or under-represented motifs in proteins, revealing species-specific adaptations.
The script outputs data tables, frequency summaries, and graphical visualizations that highlight compositional and functional differences between the two bacterial proteomes.

