# ACE2_Variant_analysis

About:

This mini-project walks through the variant analysis and biological interpretation of the ACE2 gene by using web-tools and databases. The ACE2 gene codes for the angiotensin converting enzyme. Corona virus infects the host cells by interacting with ACE2. 

Workflow:

ACE2 in GWAS Catalog -> Genome-wide significant variants(p<5e-8) -> Check in ClinVar to study the clinical significance of the variants -> Ensembl VEP for annotations -> GTEx portal -> Ensembl Linkage Disequilibrium (LD) Analysis -> miRNASNP, Regulomedb -> Biological interpretation

Results:

ClinVar returned zero results in searching for the variants listed in GWAS catalog. This is because the variants are not characterised and clinically evaluated. 4 SNPs were shortlisted from GWAS,namely, rs4830964, rs190509934, rs60768809, rs35697037 which were run by Ensembl VEP to study the consequences (missense variants). Ensembl VEP analysis showed that rs4830964 is located in the intergenic region, rs35697037 is located in the intronic region, rs60768809 is located in the intron region, and rs190509934 is located in the upstream gene region.
eQTL analysis in the GTx Portal revealed that rs4830964 could affect gene expression in tissues such as lung, esophagus-muscularis, esophagus-GIT, brain-hippocampal, artery-tibial, nerve-tibial, brain-spinal, pancreas, muscle-skeletal, thyroid and spleen. eQTL analysis of rs35697037 also demonstrated similar results. 
However, rs60768809 showed a correlation only with muscle-skeletal tissue gene expression, whereas rs190509934 returned no significant results. 
Linkage disequilibrium (LD) analysis in Ensembl indicated that rs4830964 <-> rs35697037 are in very strong LD, with R2 = 0.865, and rs35697037 <-> rs4830964 have an R2 = 1. There was no other strong evidence of linkage.
miRNASNP database returned no results when entering the variants, because they are not present in the 3’UTR region. This is concluded based on the fact that the presence of variants in the 3’UTR affects miRNA binding.
Finally, RegulomeDB displayed ranks based on the strength of evidence for the variants' presence in regulatory regions of the ACE2 gene. rs4830964 ranks highest at 1b, indicating strong regulatory evidence, followed by rs35697037 at 1f. The remaining 2 variants have lower ranks, thus indicating that there is insufficient evidence to establish that they are regulatory.

The results and discussion of this project can be referred to the document in the results folder named "ACE2 Gene Analysis_RESULTS".
