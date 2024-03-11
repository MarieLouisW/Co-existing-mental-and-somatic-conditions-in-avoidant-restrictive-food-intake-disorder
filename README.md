This file contains the complete analysis R script (de-identified) for the project "Co-existing mental and somatic conditions 
in Swedish children with the avoidant restrictive food intake disorder phenotype" by Marie-Louis Wronski, Ralf Kuja-Halkola, 
Elin Hedlund, Miriam I. Martini, Paul Lichtenstein, Sebastian Lundström, Henrik Larsson, Mark Taylor, Nadia Micali, 
Cynthia M. Bulik, and Lisa Dinkler

Corresponding author: Lisa Dinkler, PhD,
Department of Medical Epidemiology and Biostatistics, Karolinska Institutet, 
Nobels Väg 12A, 17177 Stockholm, Sweden 
E-Mail: lisa.dinkler@ki.se



File structure

1 Preliminaries
1.1 Packages
1.2 Read data sets

2 ARFID phenotype at age 9 or 12 years

3 Descriptives
3.1 Descriptives I: Case numbers for ARFID phenotype and for single criteria for MS Figure 1/SM Figure 1
3.2 Descriptives II (MS text, SM Table S1)
3.3 Descriptives III
3.4 Descriptives IV: Chi-squared tests

4 Define comorbidities - ICD chapters and single diagnoses (MS)

5 ICD Chapters - Preparation and Descriptives (MS)

6 ICD co-existing mental and somatic conditions - Preparation and Descriptives (MS)

7 ICD Condition groups - Preparation and Descriptives
7.1 Case numbers for SM Table

8 Outcome 1: Cox regression
8.1 Chapters
8.1.1 MS (Manuscript): Crude model (relative risk)
8.1.1.1 SM (Supplementary Material): Sex strata
8.1.1.2 SM: Time/age group varying model
8.1.2 MS: Absolute risks/cumulative incidence
8.2 Diagnoses/Conditions
8.2.1 MS: Crude model
8.2.1.1 SM: Sex strata
8.2.1.2 SM: Time/age group varying model
8.3 Grouped Conditions
8.3.1 MS: Crude model
8.3.1.1 SM: Sex strata
8.3.1.2 SM: Time/age group varying model

9 Outcome 2: Number of distinct diagnoses/conditions
9.1 MS: Number of distinct overall/all diagnoses
9.1.1 SM: Number of distinct overall/all diagnoses - sex differences
9.2 MS: Number of distinct mental diagnoses
9.2.1 SM: Number of distinct mental diagnoses - sex differences
9.3 MS: Number of distinct somatic diagnoses
9.3.1 SM: Number of distinct somatic diagnoses - sex differences

10 Outcome 3: Duration of inpatient treatment
10.1 MS: Duration of inpatient treatment overall/all diagnoses
10.1.1 SM: Duration of inpatient treatment overall/all diagnoses - sex differences
10.2 MS: Duration of inpatient treatment for mental diagnoses
10.2.1 SM: Duration of inpatient treatment for mental diagnoses - sex differences
10.3 Duration of inpatient treatment for somatic diagnoses
10.3.1 SM: Duration of inpatient treatment for somatic diagnoses - sex differences

11 MS: FDR/BH thresholds
11.1 SM: FDR/BH thresholds

12 MS Visualizations
12.1 Settings
12.2 Plotdata
12.3 Fig2: Barplots
12.4 Fig3: HR plots
12.5 Fig4: Cumulative incidence plots
12.6 Fig5: Histograms and IRR plots for Outcomes 2 and 3

13 Supplementary Material (SM)
13.1 Prevalence table
13.1.1 Overall
13.1.2 Per sex
13.1.3 Per age group
13.2 Coxreg tables
13.2.1 Base Model
13.2.2 Sex-stratified model
13.2.3 Age group-stratified model
13.3 Outcomes 2 + 3 tables
13.4 Fig.S1 Cumulative incidence plots for diagnoses and disorder groups
13.5 Cumulative incidence table
13.6 Fig.S2 Spline plot for ChapterF:MentalConditions
