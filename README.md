# Pharmaceutical Sales Analyst | Data Scientist | Educator

#### Technical Skills: Python, R, SQL, Tableau, PowerBI, HTML, CSS, Advanced Excel

[Resume](https://github.com/BodhiMcNally/bodhi-resume/blob/main/resume.pdf)

## Education
- **Bachelor of Science** (Data Science and Genetics & Genomics), The University of Sydney (_2022 – 2024_)  
  - **Dalyell Scholar**, **Dean’s Entry Scholarship**, **Science Top of the State Scholarship**, **Sydney Scholars Award**  
  - **Public Education Foundation Award**  

## Work Experience

**Key Account Manager (Virology - AbbVie) @ DKSH Healthcare Australia**  
_Jan 2025 – Present_  
- Drive engagement with healthcare professionals to promote a curative treatment for chronic hepatitis C.  
- Lead GP detailing, patient recall and prescriber targeting to drive uptake.
- Leverage xBERT and Veeva CRM to optimise outreach and track engagement across Australia.  
- Ensure Medicines Australia compliance and alignment with cross-functional strategies.

**Program Coordinator @ Partizan Health (now DKSH Healthcare)**  
_Jul 2024 – Dec 2024_  
- Managed 500+ patient interactions for Novo Nordisk’s WegovyCare program via 3CX, email, and Chatlio.  
- Handled patient records in a secure CRM and reported pharmacovigilance events with 100% accuracy.  
- Liaised with pharmacists, GPs, and specialists to support treatment adherence and patient care.

**Casual Academic @ The University of Sydney**  
_Jan 2024 – Present_  
- Taught tutorials and labs across DATA1001 and Statistics units for over 250 first-year students.  
- Delivered sessions on applied analytics, regression, and data wrangling.  
- Winter Intensive Instructor for Data Wrangling OLE (2024).  
- Achieved 92% positive student feedback and contributed to curriculum delivery and improvement.

**President @ Sydney University Science Society (SciSoc)**  
_Oct 2023 – Oct 2024_  
- Led Australia’s largest student society with 3,100+ members.  
- Managed 30-person team, $176K revenue, and equity programs that supported 100+ students.  
- Oversaw high-impact events, weekly operations, and long-term strategic governance initiatives.

## Certifications
- Medicines Australia Code of Conduct  
- Advanced First Aid and CPR  
- Mental Health First Aid  
- Responsible Service of Alcohol  

## Awards & Achievements
- 99.75 ATAR  
- First in NSW HSC Investigating Science  
- 2022 STANSW Young Scientist Award  

---

## Projects

### [Multi-Omics Analysis of E. coli Adaptation to Blood Environments](https://github.com/BodhiMcNally/ecoli_multiomics)  
**Tools:** R, ggplot2, MetaboAnalyst, STRINGdb, LC-MS/MS, KEGG, UniProt

This project investigated the adaptive metabolic and proteomic responses of *Escherichia coli* strain B36 when grown in human blood versus nutrient broth, with implications for sepsis research.

- Conducted proteomic profiling to identify differentially expressed proteins using Manhattan distance rankings.
- STRINGdb analysis of upregulated proteins revealed clusters in **bacterial chemotaxis**, **flagellar biosynthesis**, and the **TCA cycle**, while downregulated proteins mapped to **outer membrane proteins**, **histidine metabolism**, and **aromatic amino acid biosynthesis**.
- Targeted **LC-MS/MS metabolomics** identified 95 unique metabolites. PCA revealed strong separation between control and blood-grown cells.
- MetaboAnalyst pathway enrichment identified major shifts in **glutathione metabolism**, **TCA cycle**, and **sulphur amino acid biosynthesis**.
- Integrated findings across omics layers showed coordinated regulation of energy production (TCA & glyoxylate shunt), chemotaxis (CheA & aspartate), and adaptive nutrient acquisition (LacZ & galactose).
- These changes reflect metabolic flexibility and immune evasion strategies relevant to **pathogenicity in bloodstream infections**.

### [CRISPR-Cas9 Editing of CCR5: Sequence, Structure, and Bioethical Analysis](https://github.com/BodhiMcNally/crispr_cas9_mediated_ccr5/blob/main/GEGE2901_Advanced_Project_Paper.pdf)  
**Tools:** Geneious Prime, TMHMM, NCBI, Sequence Alignment, Protein Translation, Bioethics Literature Review

This project explored the molecular and ethical dimensions of CRISPR-Cas9 gene editing in the controversial 2018 experiment by Dr He Jiankui. The study focused on editing the **CCR5 gene**, which encodes a receptor involved in HIV entry into CD4+ T cells.

- Conducted multiple sequence alignments of wild-type CCR5 with ∆32, Lulu, and Nana mutant alleles using **Geneious Prime**, identifying nucleotide and amino acid changes.  
- Translated gene variants into protein sequences and predicted transmembrane domains using the **TMHMM Hidden Markov Model**, revealing truncated or structurally altered proteins in edited alleles.  
- Identified likely **Protospacer Adjacent Motif (PAM)** sequences that guided Cas9 editing and examined the fidelity and limitations of PAM consensus (5’-NGG-3’).  
- Analysed downstream effects of **frameshift mutations**, comparing edited variants to the natural ∆32 allele associated with HIV resistance.  
- Evaluated the **gene repair mechanisms** (NHEJ vs HDR) used and the resulting indels, frameshifts, and implications for protein function.  
- Assessed the **ethical justification and scientific validity** of the experiment, discussing off-target effects, unintended phenotypes, and the broader risks of germline gene editing.

### [Urban Resource Equity in Greater Sydney: A Multi-Metric SA2 Ranking Model](https://github.com/BodhiMcNally/urban_resource_equity_sydney/blob/main/DATA2901_Assignment.pdf)  
**Tools:** Python (Pandas, GeoPandas, Scikit-learn), PostgreSQL, Kepler.gl, PCA, Rank-Based Scoring, Spatial Analysis

As part of a group project for DATA2901, we developed a scoring model to evaluate how well-resourced different SA2 regions in Greater Sydney are across key service domains.

- Integrated and preprocessed 9 diverse datasets including **income, public transport, polling stations, schools, businesses, childcare, and libraries** using Python and SQL.
- Built a **normalised relational database** with GIST indexes for spatial joins and efficient querying of geospatial data.
- Designed a **refined scoring function** using capped z-scores weighted by **Principal Component Analysis (PCA)** to account for feature importance and limit the impact of outliers.
- Created a **rank-based alternative scoring model**, validating the original z-score model with a **Spearman's rank correlation of 0.985**.
- Developed interactive visualisations including a **Kepler.gl 3D map** and static heatmaps to highlight spatial inequality in resource distribution.
- Discovered strong clustering in well-resourced regions around the **CBD**, supported by a Pearson’s correlation coefficient of -0.654 between resource score and distance from the city centre.
- Incorporated **income correlation analysis**, finding a weak positive relationship (r = 0.293) between median income and resource access.
- Addressed **urban planning implications**, such as spatial mismatch and equity of infrastructure in suburban areas.

### [Predicting Alcohol Content in Vinho Verde Wines](https://github.com/BodhiMcNally/vinho_verde/blob/main/annotated-DATA2902-wine-and-wellbeing-report-1.pdf)  
**Tools:** R, Stepwise Regression, PCA, Cross-Validation, [R Shiny](https://bobtheboulder.shinyapps.io/VinhoPredict/), Variable Selection (`mplot`)

This project aimed to improve the precision of alcohol content labelling on Portuguese white Vinho Verde wines using data from 4,898 samples. Under Australian regulations, alcohol must be labelled within ±1.5% ABV, motivating our goal to predict alcohol content using 11 physicochemical properties.

- Conducted data cleaning and exploratory analysis on key features such as **density**, **residual sugar**, **sulphates**, and **acidity**.
- Built and refined multiple regression models using **stepwise selection (AIC)** and stability plots via the `mplot` R package.
- Identified **density** and **residual sugar** as the most predictive variables. Final model included 7 features and explained **91% of the variance** in alcohol content.
- Verified model assumptions including **linearity**, **homoscedasticity**, **normality**, and **independence** using VIF, residual plots, and QQ-plots.
- Validated model performance using **10-fold cross-validation**, comparing full and reduced models based on **MAE** and **R²**. The reduced model was chosen to minimise overfitting.
- Discussed ethical and practical considerations, including the risk of underreporting and importance of compliance with national labelling standards.

### [Assessing Coral Recovery and Reassembly in the Great Barrier Reef](https://github.com/BodhiMcNally/gbr_recovery/tree/main)  
**Client:** Dr. Ana Paula da Silva  
**Course:** STAT3926 – Statistical Consulting  
**Date:** June 2024  

This project investigated the post-disturbance recovery and reassembly of coral communities on the Great Barrier Reef using ecological and environmental datasets. Recovery was assessed as the time taken for coral cover to return to pre-disturbance levels, while reassembly was evaluated using Bray-Curtis similarity to measure changes in community composition.

We used a combination of:
- **Wilcoxon rank sum tests** to assess differences in recovery time by coral morphology, region, and shelf location  
- **Logistic regression models** to evaluate spatial and morphological predictors of successful reassembly  
- **Generalised additive models (GAMs)** to explore the relationship between sea surface temperature (SST) and disturbance frequency under RCP 4.5 and RCP 8.5 scenarios

**Key findings:**
- Median recovery time was one year, but varied significantly by coral type and location  
- 83% of reefs successfully reassembled, though no significant predictors were identified  
- SST increases are projected to raise disturbance frequency, especially under RCP 8.5  

This multi-model approach revealed the complexity of coral recovery and highlighted the need for incorporating broader environmental and biological factors in resilience assessments.

### [Forecasting Study Load at the University of Sydney](https://github.com/BodhiMcNally/usyd_revenue_forecast/tree/main)  
**Client:** Susie Chee  
**Course:** STAT3926/STAT4026 – Statistical Consulting  
**Date:** May 2024  

This consulting project involved developing a forecasting model to estimate Equivalent Full-Time Student Load (EFTSL) at the University of Sydney, in response to recent changes in government policy affecting international student enrolments.

A series of faculty-specific linear models were built, each incorporating predictors such as year, semester, fee type (CSP, DFEE, IFEE), and a dummy variable for COVID-19 impacts. A total of 24 models were created across eight faculties. These models were used to forecast 2024 EFTSL figures and assess whether the University was on track to meet its budget targets.

**Key contributions and outcomes:**
- **High-performing models:** Strong model fits for many CSP and IFEE faculty models.
- **COVID-19 & semester effects:** Impact of COVID-19 and Semester 2 enrolments were explicitly quantified.
- **Forecast vs. budget:** Projected 2024 income of **$2.42 billion**, exceeding previous years and suggesting the University is on track to meet budget targets.
- **Performance evaluation:** Compared model accuracy to existing university forecasts using MAE and annual percentage change. While the model slightly underperformed in some areas, it showed promise for refinement.
- **Limitations:** Small dataset (2018–2023) and inability to model recent behavioural changes in student enrolments due to policy shifts. Future model improvements should include more historical data and additional predictors.

This project demonstrates the use of predictive modelling to support university-level financial and enrolment planning in a changing policy landscape.

### [Enhancing Modelling Approaches for Analysing *Chalinolobus gouldii* Vocalisation Behaviour](https://github.com/BodhiMcNally/modelling_chalinolobus_gouldii_vocalisation/tree/main)  
**Client:** Magic Mei-Ting Kao  
**Course:** STAT3926/STAT4026 – Statistical Consulting  
**Date:** May 2024  

This consulting project focused on supporting a PhD candidate studying *Chalinolobus gouldii* (Gould’s wattled bat) vocalisation behaviour across various habitats. The client sought confirmation and enhancement of her statistical modelling workflow, particularly regarding the appropriateness of Generalised Linear Mixed Models (GLMMs) with nested random effects.

**Key contributions and outcomes:**
- **Model selection and validation:** Confirmed the suitability of a Poisson GLMM for modelling overall bat activity (count data), given the data’s hierarchical structure (e.g., recordings nested within sites and dates).
- **Diagnostics and fit assessments:** Verified model assumptions with residual diagnostics (using DHARMa), overdispersion tests, and zero-inflation checks—no issues were detected, supporting model robustness.
- **Interpretation of fixed effects:**  
  - **Temperature:** Significantly increased bat activity (+9% per °C, *p* < 0.01).  
  - **Reproductive periods:** Activity declined during mating (−33%) and pregnancy (−35%), both statistically significant.  
  - **Anthropogenic influence:** Significantly reduced activity (−27%, *p* < 0.05).
- **Random effects analysis:** Identified considerable variability in bat activity across sites, highlighting key hotspots (e.g., BLH_w4) and quieter zones (e.g., CTNP_duck).
- **Reproducibility and scalability:** Developed a well-documented, flexible, and reproducible GLMM workflow, suitable for application to other response variables like social call activity.

**Recommendation:**  
Continue using the enhanced Poisson GLMM framework. It is robust, interpretable, and well-suited to the client’s research aims. Further extensions can explore Bayesian methods (e.g., *brms*) for sensitivity analysis and richer inference.

This project exemplifies applied ecological modelling, statistical diagnostics, and the development of reproducible tools for interdisciplinary academic research.
