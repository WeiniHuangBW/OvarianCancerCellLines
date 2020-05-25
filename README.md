# OvarianCancerCellLines
This is the list of SNVs of resistant ovarian cancer cell samples compared to the control sample, 
which is the parental (sensitive) cell line.
The SNV list is called by Platypus based on aligned whole genome sequencing reads to reference genome Hg19.
The corresponding columns in this list refers to the sample name in the manuscirpt as follow:

NR:Number of All Reads       NV:Number of Reads with the specific SNV

OVCAR4:  GEN[0].NR             GEN[0].NV

OV4Cis:  GEN[1].NR             GEN[1].NV

OV4Cis2: GEN[2].NR             GEN[2].NV

OV4Cis5: GEN[3].NR             GEN[3].NV

OV4Cis6: GEN[4].NR             GEN[4].NV

OV4Cis7: GEN[5].NR             GEN[5].NV

Note OVCAR4 is the parential cell line before evolution and selection treatment in cisplatin, 
and used as the control sample in filtering. Thus, we see the the numbers in GEN[0].NV are zero. 
