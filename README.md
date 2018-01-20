# xixvi

### (pronounced "6-V")  /sɪks/  /viː/

Filter viromes: xix (filter in mayan) + vi (virome) 

This is a bioinformatics pipeline to clean viromes for accurate analysis

1. Quality filtering and eliminate duplicates
2. Clean clonnng vectors
3. Clean phiX17
3. Clean ribosomal rna
4. Clean human genome

5. Compare to viralrefseq
6. Compare to virulence factors
7. Compare to prophages

7. Denovo assembly 
8. Fractional abundance of each contig in the dataset

### Usage xixvi.pl [path to folder containing raw viromes] [path to resutls folder] 

### Outputs
table with numer of filtered sequences
stats about polished sequences

For each database: raw number of reads, normalized reads, fasta file with reads that map

stats for denovo assembled contigs

For each contigs database: raw number of reads, normalized reads, fasta file with reads that map
