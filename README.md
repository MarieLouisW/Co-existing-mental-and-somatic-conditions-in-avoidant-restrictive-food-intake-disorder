This file contains the complete analysis R script (de-identified) for the project "Co-existing mental and somatic conditions 
in Swedish children with the avoidant restrictive food intake disorder phenotype" by Marie-Louis Wronski, Ralf Kuja-Halkola, 
Elin Hedlund, Miriam I. Martini, Paul Lichtenstein, Sebastian Lundström, Henrik Larsson, Mark Taylor, Nadia Micali, 
Cynthia M. Bulik, and Lisa Dinkler.

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

3.1 Descriptives I for MS Figure 1 and SM Table S1

3.2 Descriptives II for MS Figure 1 and SM Table S1

3.3 Descriptives III for MS Figure 1 (ARFID phenotype criteria)

3.4 Descriptives IV for SM Table S1 (Chi-squared tests)


4 Define comorbidities - ICD chapters, individual/single diagnoses, and grouped conditions (SM Table S2)


5 ICD Chapters - Preparation and Descriptives (MS)


6 ICD Diagnoses (individual co-existing mental and somatic conditions) - Preparation and Descriptives (MS)


7 Condition groups (across ICD Chapters) - Preparation and Descriptives (MS)

7.1 Case numbers for SM Table S2


8 Cox regression models

8.1 ICD Chapters

8.1.1 MS: Crude model (Main analysis 1)

8.1.1.1 SM: Sex strata (Supplementary analysis 1)

8.1.1.2 SM: Time/age group varying model (Supplementary analysis 1)

8.1.2 MS: Absolute risks/cumulative incidence (Follow-up analysis to Main analysis 1)

8.2 ICD Diagnoses/Conditions

8.2.1 MS: Crude model (Main analysis 1)

8.2.1.1 SM: Sex strata (Supplementary analysis 1)

8.2.1.2 SM: Time/age group varying model (Supplementary analysis 1)

8.3 Grouped Conditions (across ICD chapters)

8.3.1 MS: Crude model (Main analysis 1)

8.3.1.1 SM: Sex strata (Supplementary analysis 1)

8.3.1.2 SM: Time/age group varying model (Supplementary analysis 1)


9 Number of distinct diagnoses/conditions

9.1 MS: Overall number of distinct diagnoses (Main analysis 2)

9.1.1 SM: Overall number of distinct diagnoses - sex differences (Supplementary analysis 3)

9.2 MS: Number of distinct mental diagnoses (Main analysis 2)

9.2.1 SM: Number of distinct mental diagnoses - sex differences (Supplementary analysis 3)

9.3 MS: Number of distinct somatic diagnoses (Main analysis 2)

9.3.1 SM: Number of distinct somatic diagnoses - sex differences (Supplementary analysis 3)


10 Duration of inpatient treatment

10.1 MS: Duration of inpatient treatment due to any diagnosis (Main analysis 3)

10.1.1 SM: Duration of inpatient treatment due to any diagnosis - sex differences (Supplementary analysis 4)

10.2 MS: Duration of inpatient treatment due to any mental diagnosis (Main analysis 3)

10.2.1 SM: Duration of inpatient treatment due to any mental diagnosis - sex differences (Supplementary analysis 4)

10.3 Duration of inpatient treatment due to any somatic diagnosis (Main analysis 3)

10.3.1 SM: Duration of inpatient treatment due to any somatic diagnosis - sex differences (Supplementary analysis 4)


11 MS: FDR/BH thresholds (multiple testing adjustment)

11.1 SM: FDR/BH thresholds (multiple testing adjustment)


12 MS Visualizations

12.1 Settings

12.2 Plotdata

12.3 Fig2: Barplots

12.4 Fig3: HR plots

12.5 Fig4: Cumulative incidence plots

12.6 Fig5: Histograms and IRR plots for Outcomes 2 and 3


13 SM

13.1 Prevalence table (SM Table S3)

13.1.1 Overall

13.1.2 Per sex

13.1.3 Per age group

13.2 Coxreg tables

13.2.1 Base Model (SM Table S4)

13.2.2 Sex-stratified model (SM Table S8)

13.2.3 Age group-stratified model (SM Table S11)

13.3 Tables for number of distinct diagnoses (SM Tables S6 and S9) and inpatient treatment duration (SM Tables S7 and S10)

13.4 SM Figure S1: Cumulative incidence plots for absolute risk of individual conditions

13.5 Cumulative incidence table/absolute risk assessment (SM Table S5)

13.6 SM Figure S2: Spline plot for ChapterF:MentalConditions (to visualize significant age group effect)
