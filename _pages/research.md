---
title: "Research"
layout: archive
permalink: /research/
author_profile: yes
---

Hematology, ophthalmology, and more!
---	
Currently at Genentech, I provide statistical analysis and computational support to hematology and ophthalmology studies. My past and current projects include:

- Phase Ib/II clinical trial to compare Mosunetuzumab in combination with Tiragolumab with or without Atezolizumab in patients with relapsed or refractory B-cell non-hodgkin lymphoma (NHL)
- Phase III clinical trial to study Satralizumab in participants with moderate-to-severe thyroid eye disease (TED)

Besides these therapeutic molecules, I also support computational tool and study design development through collaboration. In particular:

- With [Daniel Sjoberg](https://www.danieldsjoberg.com/): I co-develop the [admiraldiscovery](https://pharmaverse.github.io/admiraldiscovery/index.html) website, which documents the functionality of the **admiral** family of packages, a collection of open-source R packages for clinical reporting as part of the [pharmaverse movement](https://pharmaverse.org/) across biotech/pharmaceutical industry.

Estimating causal effects of organ quality and health policies in kidney transplants
---	
I worked as a research assistant to [Dr. Douglas Schaubel](https://www.dbei.med.upenn.edu/bio/douglas-e-schaubel-phd) at the University of Pennsylvania, conducting research in the intersection of survival analysis and causal inference, with applications to kidney diseases. In these projects, I performed data processing and conducted statistical analyses to: measure causal effects of transplant centers, investigate the impact of multiple waitlisting on survival, and evaluate a novel prognostic-score based weighting method for transplant center evaluation.

One project was to evaluate the impact of receiving organs from deceased-donors with Hepatitis C Virus (HCV) positive on post-transplant survival ([Schaubel et al., 2022](https://jamanetwork.com/journals/jama/article-abstract/2795744)). Patients are unweighted in the HCV- group. To address confounding in the HCV+ group, we derived a two-dimensional prognostic score, one for donors risk and one for recipients risk. The donor-associated risk score is the continuous kidney donor risk index ([KDRI](https://journals.lww.com/transplantjournal/Fulltext/2009/07270/A_Comprehensive_Risk_Quantification_Score_for.13.aspx)) while the recipient-associated risk is the [prognostic score](https://academic.oup.com/biomet/article/95/2/481/230183) estimated from the center-stratified Cox model with recipient characteristics. The two-dimensional score is then used to classify patients into risk classes, from which we obtained individual weights to generate weighted Nelson-Aalen survival curves and log-rank tests. 


Quantifying physical activity through accelerometry data from wearable devices
---	
During my internship at Regeneron, I worked with [accelerometry data](https://link.springer.com/article/10.1007/s12561-018-9227-2) from wearable devices under the mentorship of [Dr. Jacek Urbanek](https://scholar.google.com/citations?user=5X-it4IAAAAJ) and [Debra McIntyre](https://www.researchgate.net/scientific-contributions/Debra-A-Goldman-59078225/publications/2). My project focused on quantifying physical activity characteristics of minute-level accelerometry data from National Health and Nutrition Examination Survey (NHANES) and Regeneron clinical trials with the [arctools](https://cran.r-project.org/web/packages/arctools/arctools.pdf) package. We investigated NHANES as a study sample with the goal to create a pipeline for digital biomarker development for national population.

Wearable devices provide objective measurements of physical activity through an accelerometer in gravitational units. Raw data is collected in a 3D time series format, along three orthogonal axes corresponding to the device's reference frame of up-down, left-right, and backward-downward at sub-second level. These raw data is then aggregated into minute-level data and summarized by open-source reproducible metrics in non-overlapping time windows: Monitor Independent Movement Summary (MIMS), Euclidean Norm Minus One (ENMO), and Vector Magnitude Count (VMC), etc. In this project, I quantified minute-level accelerometry data from NHANES on MIMS scale for physical activity summaries and performed [harmonization mapping](https://pubmed.ncbi.nlm.nih.gov/35867392/) on internal clinical data for comparison purposes. 


Simulating wave propagation with physics-informed neural networks models  
---	
In summer 2021, I had the opportunity to participate in the [RIPS](https://www.ipam.ucla.edu/programs/student-research-programs/research-in-industrial-projects-for-students-rips-2024-los-angeles/) program at Institute for Pure and Applied Mathematics ([IPAM](https://www.ipam.ucla.edu/)), an NSF Math Institute at UCLA. I was assigned in a team of five working under the supervision of [Dr. Laurent White](https://scholar.google.com/citations?user=Q_ieoIsAAAAJ&hl=en) and [Dr. Kyung Ha](https://kyung-ha.gitlab.io/website/) to develop physics-informed neural networks ([PINN](https://towardsdatascience.com/physics-informed-neural-networks-pinns-an-intuitive-guide-fff138069563?gi=5ad447efc0df)) to simulate wave propagation with computational efficiency. Our project was sponsored by Advanced Micro Devices Inc. ([AMD](https://www.amd.com/en.html)).

Machine learning surrogate models are widely used for engineering applications thanks to the attractive computational efficiency property. However, these models suffer from a lack of extrapolation accuracy. To design an optimal network architecture to simulate wave, we embedded physics constraints, ie. PDEs of the wave equation and initial/boundary conditions, into the loss function for regularization. In addition, we sampled unlabeled input values for model training to reduce the cost of data acquisition, and extrapolated in time for acoustic wave and in space from different source locations. We presented our work at the RIPS symposium, the AMD headquarter in Santa Clara, and the Joint Mathematics Meeting 2021. 


Evaluating the performance of joint model for longitudinal and survival data
---	
In summer 2020, I had the opportunity to conduct research through the [QSURE](https://www.mskcc.org/departments/epidemiology-biostatistics/educational-opportunities/quantitative-sciences-summer-undergraduate-research-experience-qsure) program at [Memorial Sloan Kettering Cancer Center](https://www.mskcc.org/departments/epidemiology-biostatistics) under the
mentorship of [Dr. Audrey Mauguen](https://www.mskcc.org/profile/audrey-mauguen). Our goal was to investigate the association between biomarker serum bilirubin and overall survival in Primary Biliary Cirrhosis (PBC) with the Cox Proportional Hazards model, time-dependent Cox model, and Joint Model for longitudinal and time-to-event data. We then compared the estimated hazards ratios from these approaches and evaluated the benefits and drawbacks of the Joint Models. 

Intuitively, the differences in the estimated hazard ratios are due to different levels of information considered: Cox PH model uses the *baseline* values of bilirubin; time-dependent Cox uses the *current* values of bilirubin by accounting for its changes overtime; the Joint Model captures the *internal progression* of bilirubin through its measurement errors. In this project, I performed data manipulation in R, produced data visualizations, and conducted statistical analyses for survival comparisons. I presented my work at the MSK departmental symposium, the MHC Learning through Applications symposium, and the Electronic Undergraduate Statistics Research ([eUSR](https://www.causeweb.org/usproc/eusrc/2020/virtual-posters/13)) Conference 2020, for which I was awarded the [Best Video Presentation](https://www.causeweb.org/usproc/eusr/video-competition). 

During my senior year, I completed this project as my [honors thesis](/files/talk/Tran Thesis Presentation.pdf) under the supervision of Dr. Marie Ozanne, for which I was awarded the highest honors. 

Developing hierarchical Archimedean copula models for dependent data
---	
In summer 2019, I conducted my first statistical research in copula under the supervision of [Dr. Evan Ray](https://www.umass.edu/public-health-sciences/about/directory/evan-l-ray) at Mount Holyoke College. [Copula](https://en.wikipedia.org/wiki/Copula_(probability_theory)) is a joint function used to measure the dependency between random bivariates and is widely used in time series modeling. The goal of the project was to construct Archimedean copula trees with different nesting structures to develop an Archimedean random forest.

Intuitively, the more correlated covariates are grouped closer to the bottom of a nested copula tree. However, we can introduce flexibility into the tree structure by varying the number of covariates in each node, or assigning different copula families, ie. Frank, Gumbel, Clay, etc. for each node depending on its correlation property. In this project, I contributed to the *ncopula* package in R, which calculates the probability density function and cumulative distribution function to estimate parameters of nested Archimedean copulas with maximum likelihood estimation. The package also includes supplementary functions for mathematical transformations and unit tests for estimation stability. 
