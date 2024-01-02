---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Hematology and early oncology projects, and more!
---	
I work as a data scientist who provides statistical support to hematology and early oncology studies through data analysis and statistical programming. My current projects include a phase Ib/II clinical trial to compare Mosunetuzumab in combination with Tiragolumab with or without Atezolizumab in patients with relapsed or refractory B-cell non-hodgkin lymphoma, and a phase III clinical trial to study Satralizumab in participants with moderate-to-severe thyroid eye disease. 

Besides these therapeutic areas, I also support new tool development through cross-departmental collaboration. In particular, alongside [Daniel Sjoberg](https://www.danieldsjoberg.com/), I helped develop the [admiral discovery](https://pharmaverse.github.io/admiraldiscovery/index.html) website, which documents the functionality of the [admiral](https://pharmaverse.github.io/admiral/) family of packages.

Estimating causal impact of organ quality and current health policies in kidney transplantation
---	
As a graduate research assistant, I worked under the supervision of [Dr. Douglas Schaubel](https://www.dbei.med.upenn.edu/bio/douglas-e-schaubel-phd) at the University of Pennsylvania, conducting research in the interaction of survival analysis and causal inference, with applications to kidney diseases. In these projects, I performed data processing and manipulation, and conducted statistical analyses to: measure causal effects of kidney transplants centers with Standardized Mortality Ratio (SMR), investigate the impact of multiple listing with time-dependent Cox model, and evaluate a novel prognostic-score based weighting method through overall patients survival.

One project was to evaluate the impact of receiving organs from deceased-donors with Hepatitis C (HCV) positive on patients survival. Patients are unweighted in the HCV- group. To address confounding from unbalanced patient characteristics in the HCV+ group, we derived a two-dimensional prognostic score, one for donor-associated risk and one for recipient-associated risk. The donor-associated risk score is the continuous kidney donor risk index ([KDRI](https://journals.lww.com/transplantjournal/Fulltext/2009/07270/A_Comprehensive_Risk_Quantification_Score_for.13.aspx)) while the recipient-associated risk is the [prognostic score](https://academic.oup.com/biomet/article/95/2/481/230183) estimated from the center-stratified Cox model with recipient characteristics. The two-dimensional score is then used to classify patients into risk classes through its quantiles. We then obtained individual weights corresponding to specific risk score classes, to generate weighted Nelson-Aalen survival curves and log-rank tests. 


Quantifying physical activity through accelerometry data from wearable devices
---	
During my graduate biostatistics internship at [Regeneron](https://www.regeneron.com/), I worked with accelerometry data from wearable devices under the mentorship of [Dr. Jacek Urbanek](https://www.linkedin.com/in/jacek-urbanek-4b9441102/) and [Debra McIntyre](https://www.linkedin.com/in/debra-a-m-301265b/). My project focused on quantifying physical activity characteristics of minute-level accelerometry data from National Health and Nutrition Examination Survey (NHANES) and Regeneron clinical trials with the open source package [Arctools package](https://cran.r-project.org/web/packages/arctools/index.html) in R. We investigated NHANES as a study sample to understand more the national population with the goal to create a pipeline for digital biomarker development.

Wearable devices provide objective measurements of physical activity by using an accelerometer that measures the acceleration amplitude in gravitational units. Raw data is collected in a three-dimensional time series format, along three orthogonal axes corresponding to the device's reference frame of up-down, left-right, and backward-downward. Raw data is usually collected at sub-second level and then aggregated into minute-level data. There are several open-source reproducible metrics that summarize this minute-level data in non-overlapping time windows such as: Monitor Independent Movement Summary (MIMS), Euclidean Norm Minus One (ENMO), and Vector Magnitude Count (VMC), etc. In this project, I quantified minute-level accelerometry data from NHANES on MIMS for physical activity summaries and [mapped](https://pubmed.ncbi.nlm.nih.gov/35867392/) company clinical data from onto the same scale for comparison purposes. 


Simulating wave propagation with physics-informed neural networks models  
---	
In summer 2021, I had the opportunity to participate in the [RIPS](https://www.ipam.ucla.edu/programs/student-research-programs/research-in-industrial-projects-for-students-rips-2024-los-angeles/) program at Institute for Pure and Applied Mathematics ([IPAM](https://www.ipam.ucla.edu/)), an NSF Math Institute at UCLA. I was assigned in a team of five working under the supervision of [Dr. Laurent White](https://www.linkedin.com/in/laurent-white/) and [Dr. Kyung Ha](https://www.linkedin.com/in/kyung-ha-850894240/) to develop physics-informed neural networks ([PINN](https://towardsdatascience.com/physics-informed-neural-networks-pinns-an-intuitive-guide-fff138069563?gi=5ad447efc0df)) to simulate wave propagation with computational efficiency. Our project was sponsored by Advanced Micro Devices Inc. ([AMD](https://www.amd.com/en.html))

Machine learning surrogate models are widely used for engineering applications thanks to the attractive computational efficiency property. However, these models suffer from a lack of extrapolation accuracy. To design an optimal network architecture, we embedded physics constraints, ie. PDEs of the wave equation and initial/boundary conditions, into the loss function for regularization purposes. In addition, we sampled unlabeled data points to reduce the cost of data acquisition. We presented our work at the RIPS symposium, the AMD headquarter in Santa Clara, and the Joint Mathematics Meeting 2021. 


Evaluating the performance of joint model for longitudinal and survival data
---	
In summer 2020, I had the opportunity to conduct research through the [QSURE](https://www.mskcc.org/departments/epidemiology-biostatistics/educational-opportunities/quantitative-sciences-summer-undergraduate-research-experience-qsure) program at [Memorial Sloan Kettering Cancer Center](https://www.mskcc.org/departments/epidemiology-biostatistics) under the
mentorship of [Dr. Audrey Mauguen](https://www.mskcc.org/profile/audrey-mauguen). The goal of the project was to investigate the association between biomarker serum bilirubin and overall survival in Primary Biliary Cirrhosis (PBC) with the Cox Proportional Hazards model, time-dependent Cox model, and Joint Model for longitudinal and time-to-event data. We then compared the estimated hazards ratios from these three different approaches and evaluated the benefits and drawbacks of the Joint Models. 

Intuitively, the differences in the estimated hazard ratios are due to different levels of information considered: the Cox PH model uses the {\em baseline} values of bilirubin; time-dependent Cox uses the {\em current} values of bilirubin by accounting for its changes overtime; the Joint Model captures the {\em internal progression} of bilirubin through its measurement errors. In this project, I performed data manipulation in R, produced data visualizations, and conducted statistical analyses for survival comparisons. I presented my work at the MSK departmental symposium, the MHC Learning through Applications symposium, and the Electronic Undergraduate Statistics Research ([eUSR](https://www.causeweb.org/usproc/eusrc/2020/virtual-posters/13)) Conference 2020, for which I was awarded the [Best Video Presentation](https://www.causeweb.org/usproc/eusr/video-competition). 

During my senior year, I completed this project as my honors thesis under the supervision of Dr. Marie Ozanne, for which I was awarded the highest honors. 

Developing hierarchical Archimedean copula models for dependent data
---	
In summer 2019, I conducted my first biostatistical research in copula under the supervision of [Dr. Evan Ray](https://www.evanlray.com/) at Mount Holyoke College. Copula is a joint function used to measure the dependence between random variables and is widely used in times series modeling. The goal of the project was to construct Archimedean copula trees with different nesting structures to develop an Archimedean random forest.

Intuitively, the most correlated the covariates are grouped in the bottom of a nested copula tree. However, we can introduce flexibility into the tree structure by varying the number of covariates in each node, or assigning different copula families, ie. Frank, Gumbel, Clay, etc. for each node depending on its correlation property. In this project, I contributed to the {\em ncopula} package in R, which calculates the probability density function and cumulative distribution function to estimate parameters of nested Archimedean copulas with maximum likelihood
estimation. The package also includes supplementary functions for mathematical transformations and unit tests for estimation stability. 
