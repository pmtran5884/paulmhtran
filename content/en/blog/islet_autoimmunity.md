---
date: "2020-11-06T12:04:06-05:00"
tags:
- polygenic risk score
- type 1 diabetes
- islet autoimmunity
- newborn screening
- genetics
title: Genetic risk of islet autoimmunity
---

Type 1 diabetes is a autoimmune condition where an environemental stimulus triggers immune targeting of pancreatic islets in geneticaly susceptible individuals. Twin concordance studies have estimated the genetic heritability to be X%. Regression methods have estimated genetic heritability to be Y%. The human leukocyte antigen loci have the strongest associations with this condition. Most of the other associated SNPs are in immune function pathways, but they have much lower effect sizes compared to the HLA loci. 

Islet autoantibodies were discovered in 200X and are strongly associated with developing type 1 diabetes. Natural history studies have found that X%, y%, and z% of 1, 2, 3 autoantibody positive individuals develop type 1 diabetes, respectively. 

Numerous trials have tested methods to prevent autoantibody positive individuals from progressing to type 1 diabetes to no avail. However, several successes have been noted in preventing genetic susceptible individuals from progressing to islet autoimmunity and type 1 diabetes. Genetically susceptible individuals were defined as a newborn with a first degree relative diagnosed with type 1 diabetes. These individuals have a 10% chance of developing type 1 diabetes. Because of the low seroconversion rate of these individuals, these trials are slow to accrue enough participants and take X-Y years to complete. A genetic risk stratification method which identifies individuals at higher risk of islet autoantibody seroconversion could improve the power of trials and reduce the time necessary to recruit enough subjects.

While many genetic risk scores have been developed for predicting risk of type 1 diabetes, none have been developed specifically for predicting risk of islet autoimmunity. Additionally, these approaches only capture a subset of genome wide significant SNPs. Numerous studies have demonstrated the importance of the non-genome wide significant SNPs in contributing to polygenic risk. Most type 1 diabetes genetic studies have not used a genome wide SNP chip, but rather the Immunochip, which is more specific to SNP regions associated with autoimmunity. Thus, this may not capture the whole genome SNP heritability.

We sought to estimate the immunochip genetic risk of developing islet autoimmunity and determine the optimal threshold for enrolling high genetic risk patients in future clinical trials for preventing islet autoimmunity.


Results outline:
1. GWAS of combined ASP and case-control dataset with a linear mixed model with genetic relationship matrix as random effects

We downloaded affected sib pair and case-control data for type 1 diabetes from the T1DGC through dbGaP. The data were processed through standard GWAS quality control. We estimated the genetic relationship amongst the individuals. We fit these relationships as random effects in a linear mixed model with the SNPs measured on immunochip as fixed effects. The GWAS found X genome-wide significant SNPs (Figure 1). Compared to the GWAS conducted by Barret et al, we found X more/less genome-wide significant SNPs and SNPs in general had more/less significance. 

2. PRS

We developed a PRS from the immunochip GWAS using LDclump and LDpred and found that X developed the most predictive PRS based on X-fold cross validation. The clumping kept Y SNPs in the PRS. We found the PRS has an AUC of X. The model is well calibrated (Figure 2A).

2. Estimation of positive predictive value of PRS for islet autoimmunity

While the PRS was trained on case-control and affected sib pair data, we wanted to validate it on predicting islet autoantibody status. The time-dependent AUROC at 3, 5, and 10 years were X, Y, and Z (Figure 2B). At three years, X, Y, and Z% of individuals in the top quintile of genetic risk developed 1, 2, and 3 autoantibodies, respectively (Figure 2C).  

3. Caucasian proportion of high genetic risk individuals based on UK Biobank data

We downloaded UK Biobank data and performed SNP imputation using the 1000 genomes data. We extracted the SNPs in our PRS and applied it to the UK Biobank genotypes. At each quintile of genetic risk from our PRS, we found V, W, X, Y, and Z% of indivudals (Figure 2D).

4. Optimal threshold for population level genetic risk screening

The most well-powered trial for islet autoimmunity prevention would maximize the number of individuals who develop islet autoimmunity at trial termination. This value depends on the portion of the population deemed high risk multiplied by the positive predictive value of the PRS at the prespecified threshold. Using the proportions calculated from the representative UK Biobank data and the PPV from the TEDDY study, we approximated the proportion of the full population predicted to develop two or more islet autoantibodies for different PRS thresholds (Figure 3). We found that W% is the optimal threshold, at which the proportion of the population deemed high risk is X%, the positive predictive value is Y%, and the proportion of individuals out of the full population predicted to develop 2 or more islet autoantibodies is Z%.

Figure 1. A) Manhattan plot B) Pairs plot of p-values from Nat genetics publication compared to our p-values

Figure 2. A) PRS ROC and Calibration Curve from T1DGC data B) PRS time-dependent ROC from TEDDY data C) Kaplan-Meier curves of risk of developing islet autoantibodies from TEDDY data D) Proportion of UK biobank population at each quintile of risk

Figure 3. Plot of proportion of full population predicted to develop two or more positive islet autoantibodies vs PRS threshold

Discussion:

The published GRS2 score has an AUC of X% on the T1DGC dataset while our PRS has an AUC of Y%.

Limitations: This PRS is likely weaker in non-Caucasian populations since the GWAS studies used for this score are predominantly Caucasian. This PRS does not account for interaction effects among HLA SNPs and from HLA to non-HLA SNPs which may play a stronger role in type 1 diabetes compared to other polygenic traits. The PRS generated is based on immunochip data, future populations with a larger whole genome SNP chip of WES/WGS data may yield more common and rare variants contributing to islet autoimmunity. The PRS is trained on type 1 diabetes status rather than islet autoantibody status since no large scale genetic data is available for islet autoantibody vs no islet autoantibody.

Conclusion: Our method of defining high genetic risk individuals should improve the pair of islet autoimmunity prevention trials compared to the current first degree relative strategy. 
