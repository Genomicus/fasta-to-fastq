# Introduction #
The program simply converts FASTA format to FASTQ format while assuming quality score of 40. Users can define the quality score of each reads as well (coming up and as we get along with other features as well).

**Usage (standalone)**
```
perl fasta_to_fastq.pl reads.fasta > my_converted_fasta.fq
```

**Usage (as part of a workflow in unix)**
```
do_something_that_outputs_fasta.o | perl fasta_to_fastq.pl - > my_converted_fasta.fq
```