###Week 4

##Trinity

Number of trinity transcripts 122,909

##Transdecoder

Number of ORFs detected:68,684

Number of complete ORFs: 32,234

Number of 5' partial ORFs: 18,336

Number of 3' partial ORFs: 6,941

Number of internal ORFs: 11,173

##Blast output
Number of unique ORFs annotated: 34,249

Number of unique annotations: 12,037

Name and number of most common annotation: sp|Q09666|AHNK_HUMAN and had a number of 1,359
##Trinity
Using the assigned liver SRR11284036 umber, i was able to clean and trim reads. I was able to make a Trinity.fasta file from this.

##Transdecoder
After creating a Trinity.fasta file, I ran a Transdecoder command to look for open reading frames in my assembly.
Every single transcript is looked at, "is it complete,is it an internal sequence, 5' or 3' end."
 After running, four different files were created; longest_orfs.cds (protein coding gene), .pep (translated amino acids), .gff3 and base_freqs.dat (all fasta files).
## Blast output
Blasp was run (protein to protein), followed by query longest_orfs.pep, swissProt/uniprot, etc...
In this directory, you will find several columns that consist of the transcript name, query, hit, percent similarity, mismatches, evalue, bitscore etc...
This is used to find genes similar to our transcripts, using blast.

