# Get-Multiple-Genes

GenBank Processing and Visualization Tool

Overview

This script is designed to process GenBank (.gbk) files and analyze CDS (Coding Sequence) information. The tool provides insights into the counts of CDSs, hypothetical proteins, and non-hypothetical genes in genomic data. Additionally, the script generates a stacked bar chart to visualize these counts, displaying the percentage contribution of hypothetical and non-hypothetical proteins for each genome.

Features

Batch Analysis of GenBank Files:

Analyzes all .gbk files in a specified folder.
Extracts the following details:
Total CDS count.
Number of products (/product=).
Number of genes (/gene=).
Hypothetical protein count (/product="hypothetical protein").
Non-hypothetical gene count.
Excel Output:

Saves the analyzed data into an Excel file with organized columns:
Genome: File name of the genome.
CDS Count: Total number of CDSs in the file.
Product Count: Number of CDSs with a /product= annotation.
Gene Count: Number of CDSs with a /gene= annotation.
Hypothetical Protein Count: Count of hypothetical proteins.
Non-Hypothetical Gene Count: Count of non-hypothetical proteins.
Visualization:

Generates a stacked bar chart (.svg file):
X-axis: Genome names.
Y-axis: Total CDS count.
Hypothetical and non-hypothetical protein counts are stacked.
Displays percentage labels within each bar for hypothetical and non-hypothetical proteins.
