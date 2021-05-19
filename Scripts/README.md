## File Generate_new_variant_id_snp_lookup_table_covariates.ipynb: 
In order to better record the SNPs information, new variant names constructed as "chromosome_location_REF_ALE".
snp_lookup_table contains both new variant id and rs id that will add to final results.

## WES_variant_calling.sh
This sh file contains the pipeline for raw WES data's pre-processing and variant calling using HaploytypeCaller and Mutect2. 
This was processed in each patient's data and combined to a sum vcf later.

## RNA_seq_align_and_quantification.sh
This sh file contatins the pipeline for raw RNA-seq data's pre-processing and quantification using RNA-SeQC.
Same to WES data, this generated gene expression TPM data for each patients and combined to a sum file later.

## plotEQTL.R
This R script is used for generating box plots for selected SNP-Gene pairs.

## Hail_split.ipynb
Hail v0.2 used to split multialleic sites to bialleic sites.