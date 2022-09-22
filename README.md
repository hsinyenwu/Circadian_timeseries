### Circadian_timeseries
Project information and goal for Joey

### Datasets:
1. **Dataset 1**:  
**A. Paper**: [Global transcriptome analysis reveals circadian control of splicing events in Arabidopsis thaliana. Plant Journal 2020](https://onlinelibrary.wiley.com/doi/full/10.1111/tpj.14776)  
**B. Growth conditions**: RNA-seq of circadian timeseries sampling (LL2-3) of 13-14 day old Arabidopsis thaliana Col-0 (24 h to 68 h, sampled every 4 h). Grown under LD 12h:12h. 2 biological replicates  
**C. Data**: [Data link](https://www.ebi.ac.uk/arrayexpress/experiments/E-MTAB-7933/samples/)  
**D. RNA-seq exp**: (from the paper) **Total RNA** was extracted, and **non-stranded sequencing libraries** (TruSeq RNA v2) were prepared from **polyA purified RNA**. Libraries were then sequenced on an Illumina HiSeq 2500 high-throughput sequencer using two flow-cell lanes (see Experimental Procedures section for more details). The data generated here represent more than 361 million short nucleotide reads (**100 bp single end**) and 36.1 Gb of successfully aligned sequence

2. **Dataset 2**:  
**A. Paper**: [The circadian clock shapes the Arabidopsis transcriptome by regulating alternative splicing and alternative polyadenylation](https://www.jbc.org/article/S0021-9258(17)49454-3/fulltext)  
**B. Growth conditions**: Seeds of A. thaliana ecotype Columbia (Col-0) were surface-sterilized, stratified for 2 days at 4 °C, and then planted on a Murashige and Skoog plate. The seedlings were grown under long-day conditions (16 h light/8 h dark) with a cool white fluorescent light at 24 °C for 8 days. Then they were transferred to continuous light or kept under long-day conditions at 24 °C for an additional 2 days to explore circadian and diurnal regulation. To determine the oscillating transcriptome, about 30 seedlings were collected at 3-h intervals (ZT2, ZT5, ZT8, ZT11, ZT14, ZT17, ZT20, and ZT23). Two biological replicates at each time point were utilized.  
**C. Data**: [GSE137732](http://www.ncbi.nlm.nih.gov/entrez/query.fcgi?cmd=search&db=nucleotide&doptcmdl=genbank&term=GSE137732)  
**D. RNA-seq exp**: Total RNA from seedlings collected at different time points was isolated using the RNeasy Plant Mini Kit (Qiagen) and treated with the Turbo DNA-free Kit (Invitrogen) following the manufacturer's instructions. Library preparation and strand-specific paired-end sequencing (2 × 150 bp) on a HiSeq 4000 platform (Illumina) were performed by Novogene.  

### Procedures:
1. Download the data  
2. Remove adaptor  
3. Map reads to transcriptome with Kallisto  
4. Use the TPM value from Kallisto for running [JTK cycle](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3119870/)  
5. Write a R Shiny app for presenting the result  
6. Create a GitHub page  
