# BIF7104-GATK
Tutorial (skipping PoN for now): https://gatk.broadinstitute.org/hc/en-us/articles/360047232772--Notebook-Intro-to-using-Mutect2-for-somatic-data

my setup: 

      └── gatk-4.6.2.0/
         └── GATK_Mutect2_Tutorial/
            └── scripts

1. cd ../gatk-4.6.2.0/GATK_Mutect2_Tutorial/scripts
2. bash directory_setup
3. bash file_setup
4. bash call_somatic_SNVs_and_indels
5. bash pileup_summary
6. bash estimate_contamination
7. bash filter
8. igv:
   
i. File -> Load from URL
gs://gatk-tutorials/workshop_2002/3-somatic/mutect2_precomputed/9_somatic_oncefiltered.vcf.gz

ii. File -> Load from File
path/to/gatk-4.6.2.0/GATK_Mutect2_Tutorial/notebooks/sandbox/2_tumor_normal_m2.bam

iii. File -> Load from URL
gs://gatk-tutorials/workshop_2002/3-somatic/bams/tumor.bam

iv. File -> Load from File
gs://gatk-tutorials/workshop_2002/3-somatic/bams/normal.bam

9. bash funcotator
10. bash examine_mutations

