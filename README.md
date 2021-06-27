# Embracing the uncertainty of Deep Learning models to support clinical decision making for Mental Health Conditions

This repository contains the code for Ram Popat's master's thesis at Imperial College London, supervised by Dr Julia Ive and the second marker is Dr Mark van der Wilk. If you use this code, please cite in the following way:

@UNPUBLISHED{popatuncertainty2021,
author={Ram Popat},
title={Embracing the uncertainty of Deep Learning models to support clinical decision making for Mental Health Conditions},
note={Intend to publish soon},
month={6},
year={2021}
}

-----
Repository Contents:

This repository contains four Colab Notebooks. I suggest that you press the ''Open in Colab'' link at the top when you open a file. We used Colab notebooks for ease of GPU access. The four notebooks are as follows and there is a description inside each notebook with a table of contents in a markdown hierarchy:

1. Main_Notebook_DementiaBank.ipynb - This contains the code for the Bayesian Deep Learning and Referral Learning models and Active Learning implementation for the DementiaBank dataset [1]. This includes the data and machine learning pipelines.
2. Main_Notebook_MIMIC.ipynb - Same as 1 but for the MIMIC dataset with Phenotype Annotation [2, 3, 4, 5].
3. Uncertainty_Analysis.ipynb - This contains the code for the Referral Learning strategies and different uncertainty-based plots and tables in the thesis.
4. Performance_Analysis.ipynb - This contains the code for producing the performance plots and tables in the thesis.

-----
References:

[1] Becker, J. T., Boller, F., Lopez, O. L., Saxton, J., & McGonigle, K. L. (1994). The natural history of Alzheimer's disease: description of study cohort and accuracy of diagnosis. Archives of Neurology, 51(6), 585-594.

[2] Johnson AE, Pollard TJ, Shen L, Lehman LwH, Feng M, Ghassemi M et al. ‘MIMIC-III, a freelyaccessible critical care database’. In:Scientific Data3.1 (May 2016), p. 160035. url:https://www.nature.com/articles/sdata201635.pdf

[3]  Johnson A, Pollard T and Mark R. ‘MIMIC-III Clinical Database’. In: (2020). url:https://physionet.org/content/mimiciii/1.4/

[4]  Gehrmann S, Dernoncourt F, Li Y, Carlson ET, Wu JT, Welt J et al. ‘Comparing deep learning andconcept extraction based methods for patient phenotyping from clinical narratives’. In:PLOS ONE13(Feb. 2018), pp. 1–19. url:https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0192360 

[5]  Moseley E, Celi LA, Wu J and Dernoncourt F. ‘Phenotype Annotations for Patient Notes in the MIMIC-III Database’. In: (2020). url:https://physionet.org/content/phenotype-annotations-mimic/1.20.03/
