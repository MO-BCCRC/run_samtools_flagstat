#run_samtools_flgastat: generated stats for bam file


```
Development information

date created : Mar 25 2015
last update  : Mar 25 2015
Developer    : Diljot Grewal (dgrewal@bccrc.ca)
Input        : Bam file
Output       : statistics for the bam (text file)
Seed used    : Samtools

```


###Usage
This component should be used generally after the alignment process is complete, generates stats for sanity check.

###Dependencies

- python
- samtools


###Example

The behaviour of this components is equivalent to this command :

`samtools flagstat alignment.bam > alignment.bamstats`



###Known issues



###Last updates

