Workflow of microbiome analysis using shotgun sequencing data. 
This script shows an example of the standard workflow for microbiome analysis (standard workflow for both Shotgun and 16S sequencing data): 
1. Alpha diversity
2. Beta diversity (e.g. Ordination; PCoA plot; Euclidean distance)
3. PERMANOVA
4. Differential abundant analysis (e.g. Maaslin2, LEfSe, DESeq2, ANCOMBC, etc.)

In the example of shotgun metagenomics sequencing input dataset, the raw sequence data (normally in FASTA or FASTQ format) are processed using BioBakery workflows. Kneaddata were used for quality filtering, MetaPhlAn were used for taxa classification up to species taxonomic level (Metaphlan4 now provides highest resolution up to species-level genome bins (SGBs)) and HUMAnN for functional pathway annotation. 

KneadData: https://github.com/biobakery/kneaddata

Metaphlan 4.0: https://github.com/biobakery/MetaPhlAn/wiki/MetaPhlAn-4

Humann 3.0: https://github.com/biobakery/humann


