### Circadian_timeseries
Project information and goal for Joey

1. **Dataset1**: 
**A. Paper**: [Global transcriptome analysis reveals circadian control of splicing events in Arabidopsis thaliana. Plant Journal 2020](https://onlinelibrary.wiley.com/doi/full/10.1111/tpj.14776)  
**B. Growth condition**: RNA-seq of circadian timeseries sampling (LL2-3) of 13-14 day old Arabidopsis thaliana Col-0 (24 h to 68 h, sampled every 4 h). Grown under LD 12h:12h. 2 biological replicates  
**C. Data**: [Data link](https://www.ebi.ac.uk/arrayexpress/experiments/E-MTAB-7933/samples/)  
**D. RNA-seq exp**: (from the paper) **Total RNA** was extracted, and **non-stranded sequencing libraries** (TruSeq RNA v2) were prepared from **polyA purified RNA**. Libraries were then sequenced on an Illumina HiSeq 2500 high-throughput sequencer using two flow-cell lanes (see Experimental Procedures section for more details). The data generated here represent more than 361 million short nucleotide reads (**100 bp single end**) and 36.1 Gb of successfully aligned sequence

**Procedure**:
1. Download the data
2. Remove adaptor
3. Map reads to transcriptome with Kallisto
4. Use the TPM value from Kallisto for running [JTK cycle](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3119870/)
5. Write a R Shiny app for presenting the result

