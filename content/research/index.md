---
title: "Research"
description: "Overview of my scientific interests."
summary: "Overview of my scientific interests."
---

## Genetic regulation of molecular phenotypes

![QQ plot showing results from the differential regulation analysis by bootstrapping (DRAB) method.](drab_qq.png)

Genetic information is the blueprint for life, but gene transcripts and assembled proteins are its building blocks. I am interested in understanding how changes in our genetic code regulate the expression of genes, proteins, metabolites, and other molecular phenotypes. Which genetic variants function as quantitative trait loci (QTLs), and how can we fine-map them more precisely? Can we train more accurate models for predicting expression? How do the patterns of genetic regulation differ across tissue and cellular contexts, and how are they disrupted by disease-associated variants?

In one of my dissertation projects, for example, I developed the [differential regulation analysis by bootstrapping (DRAB)](https://projecteuclid.org/journals/annals-of-applied-statistics/volume-18/issue-3/A-bootstrap-model-comparison-test-for-identifying-genes-with-context/10.1214/23-AOAS1859.full) method to identify molecular phenotypes with context-specific patterns of genetic regulation. This involved training models that can learn tissue-specific genetic regulatory patterns and then testing them for equivalence using a novel model comparison test. My bootstrap-based model comparison test can determine if any two machine learning models are equivalent at the population level, so it also has broad applications beyond computational biology.

## Transcriptome- and proteome-wide association studies

![Schematic diagram of the co-expression-wide association study (COWAS) method.](cowas_diagram.png)

Once we have mapped the genetic variants that influence expression and aggregated them into a prediction model, the natural next step is to use this information to identify genes whose genetically regulated expression is associated with downstream traits. The transcriptome-wide association study (TWAS) method does just that, and related approaches such as the proteome-wide association study (PWAS) extend the TWAS framework to proteins and other omic data types. I am interested in further improving and extending this class of methods. Does genetically regulated expression have nonlinear effects on complex traits, and how can we model nonlinearity within the two-stage least squares framework? Are genetic effects on disease risk mediated through single genes or larger networks? What are the most relevant omic layers for a given phenotype, and how can we integrate multi-omic evidence to gain a fuller picture of the pathways underlying complex traits?

In another part of my dissertation, I introduced the [co-expression-wide association study (COWAS)](https://www.nature.com/articles/s41467-025-66039-6) method to perform association testing with genetically regulated expression. Unlike previously developed methods, which consider each gene or protein individually, COWAS trains models to predict the co-expression of pairs of molecular exposures. By jointly testing whether an outcome trait is associated with each exposure and with their co-expression, COWAS is able to disentangle direct and interaction effects while also boosting power relative to standard TWAS and PWAS.

## Infectious disease dynamics

![Plots of population dynamics over time under different infectious disease control strategies.](wns_plot.png)

Before I turned my attention to statistical genetics, I worked on mathematical models of population dynamics. I was especially interested in using differential equation models to understand the spread of infectious diseases between multiple populations, both in humans and wildlife. By posing models that reflect organismal and pathogen lifecycles along with their migration patterns, I sought to prioritize more effective interventions to control the spread of disease. Although mathematical biology is no longer my primary focus, I enjoy thinking about complex dynamical systems and am always open to collaborations in this space.

For example, in [my first published research project](https://onlinelibrary.wiley.com/doi/10.1111/nrm.12304), I modeled the impact of hypothetical control strategies on the long-term survival of bat populations affected by white-nose syndrome. My work improved on previous models by accounting for metapopulation dynamics and more accurately capturing seasonal activity patterns, leading to practical recommendations for mitigating the impact of this highly infectious fungal disease.
