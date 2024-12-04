# Practice_3
4.12.24
data: 
- SRR292678 - paired end, insert size 470 bp (forward reads, reverse reads, 400 Mb each)
- SRR292862 – mate pair, insert size 2 kb, (forward reads, reverse reads, 200 Mb each)
- SRR292770 – mate pair, insert size 6 kb, (forward reads, reverse reads, 200 Mb each)

**for lab report number of reads:** ...

FASTQC report: fastqc -t 1 -o ./QC_Trimming 

assembly: spades.py -1  -o ecoli_assembly
