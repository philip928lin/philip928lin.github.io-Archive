---
title: "HydroCNHS: A Python Package of Hydrological Model for Coupled Natural Human Systems"
collection: publications
permalink: /publication/2022-JWRPM
excerpt: 'This paper is about an open-source Python package of hydrological model for coupled natural human systems.'
date: 2022-12-2
venue: 'Journal of Water Resources Planning and Management'
paperurl: 'https://doi.org/10.1061/(ASCE)WR.1943-5452.0001630'
citation: '<b>Lin, C. Y.</b>, Yang, Y. C. E., & Wi S. (2022). HydroCNHS: A Python Package of Hydrological Model for Coupled Natural Human Systems, <i>Journal of Water Resources Planning and Management, 148(12), 6022005.</i>.'
---
Modeling coupled natural–human systems (CNHS) to inform comprehensive water resources management policies or describe hydrological cycles in the Anthropocene has become popular in recent years. To fulfill this need, we developed a semidistributed hydrological model for coupled natural–human systems, HydroCNHS. HydroCNHS is an open-source Python package supporting four application programming interfaces (APIs) that enable users to integrate their human decision models, which can be programmed with the agent-based modeling concept, into HydroCNHS. Specifically, we designed Dam API, RiverDiv API, Conveying API, and InSitu API to integrate, respectively, customized man-made infrastructures such as reservoirs, off-stream diversions, transbasin aqueducts, and drainage systems that abstract human behaviors (e.g., operator and farmer water use decisions). Each of the HydroCNHS APIs has a unique plug-in structure that respects within-subbasin and inter-subbasin (i.e., river) routing logic for maintaining the water balance. In addition, HydroCNHS uses a single model configuration file to organize input features for the hydrological model and case-specific human systems models. Also, HydroCNHS enables model calibration using parallel computing power. We demonstrate the functionalities of the HydroCNHS package through a case study in the Northwest United States. Given the integrity of the modeling framework, HydroCNHS can benefit water resources planning and management in various aspects, including uncertainty analysis in CNHS modeling and more complex agent design.

[Download](https://github.com/philip928lin/philip928lin.github.io/raw/main/files/Lin_et_al-2022-JWRPM.pdf)

Software link: https://github.com/philip928lin/HydroCNHS
HydroCNHS manual: https://hydrocnhs.readthedocs.io/