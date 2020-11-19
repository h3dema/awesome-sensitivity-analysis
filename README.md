# awesome-sensitivity-analysis [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/h3dema/awesome-sensitivity-analysis)

A list of videos, books and paper about Sensitivity analysis


## Books and papers

There are several books about the topic.

* Borgonovo, Emanuele. **Sensitivity Analysis: An Introduction for the Management Scientist**. 2017. Springer International Publishing. ISBN 978-3-319-52259-3. https://www.springer.com/gp/book/9783319522579
  - This book is an introduction to the methodology of sensitivity analysis of model output. Primarily intended for people that are familiar with mathematical models but less familiar with the techniques for performing sensitivity analysis.

* From Cacuci
  - Cacuci, D. G., Ionescu-Bujor, M., & Navon, I. M. (2005). **Sensitivity and uncertainty analysis, volume II: applications to large-scale systems** (Vol. 2). CRC press.
  - [Paper] Cacuci, D. G., & Ionescu-Bujor, M. (2004). **A comparative review of sensitivity and uncertainty analysis of large-scale systems—II: statistical methods**. Nuclear science and engineering, 147(3), 204-217.
  - Cacuci, D. G. **Sensitivity and Uncertainty Analysis: Theory**. Volume 1. (2003).
  
* From Saltelli
  - Saltelli, A., Ratto, M., Andres, T., Campolongo, F., Cariboni, J., Gatelli, D., ... & Tarantola, S. (2008). **Global sensitivity analysis: the primer**. John Wiley & Sons.
  - Saltelli, A., Tarantola, S., Campolongo, F., & Ratto, M. (2004). **Sensitivity analysis in practice: a guide to assessing scientific models (Vol. 1)**. New York: Wiley.
  - Saltelli, A., & Chan, K. **Sensitivity analysis: gauging the worth of scientific models**. 2000. New York: Wiley.

* Yeung, D. S., Cloete, I., Shi, D., & wY Ng, W. **Sensitivity analysis for neural networks**. (2010). Springer-Verlag Berlin Heidelberg. ISBN
978-3-642-02531-0. https://www.springer.com/gp/book/9783642025310
  - This book is a good help for researchers working with _neural networks_ and machine learning.

* Insua, D. R. **Sensitivity analysis in multi-objective decision making**. In Sensitivity Analysis in Multi-objective Decision Making (1990). Springer, Berlin, Heidelberg. ISBN 978-3-642-51656-6. https://www.springer.com/gp/book/9783540526926

* NIST/SEMATECH **e-Handbook of Statistical Methods**. https://www.itl.nist.gov/div898/handbook/ or https://doi.org/10.18434/M32189.
  - A large collection of statistics methods. Well organized, and covers lots of topics, including statistical analysis. The full handbook can be downloaded as a pdf file [here](https://www.itl.nist.gov/div898/handbook/toolaids/pff/E-Handbook.pdf).

* SHAP (SHapley Additive exPlanations) values
  - Lundberg, S. M., & Lee, S. I. (2017). **A unified approach to interpreting model predictions**. In Advances in neural information processing systems (pp. 4765-4774). http://papers.nips.cc/paper/7062-a-unified-approach-to-interpreting-model-predictions
  - Lundberg, S. M., Erion, G., Chen, H., DeGrave, A., Prutkin, J. M., Nair, B., ... & Lee, S. I. (2020). **From local explanations to global understanding with explainable AI for trees**. Nature machine intelligence, 2(1), 2522-5839. https://rdcu.be/b0z70
  - Lundberg, Scott M., et al. **Explainable machine-learning predictions for the prevention of hypoxaemia during surgery**. Nature biomedical engineering 2.10 (2018): 749-760. https://rdcu.be/baVbR

## Machine learning explanability

* https://github.com/jphall663/awesome-machine-learning-interpretability
  - a very good list of machine learning interpretability resources.
* https://github.com/jnikhilreddy/Explainable-AI-papers-Year-wise
  - a list of papers in the area of Explainable Artificial Intelligence from 2014 up to 2020 (when I last checked).

## Videos

| Video                | Lecturer | Description | URL                                         |
|----------------------|----------|-------------|---------------------------------------------|
| Sensitivity analysis | Jelena Srebric | Summary of local and global methods | https://www.youtube.com/watch?v=3wNxZcvRdPI |
| Using the SALib library for conducting sensitivity analyses of models | Will Usher | Presentation at PyData 2015 about a library that performs sensitivity analysis on Python with step-by-step examples | https://www.youtube.com/watch?v=gkR_lz5OptU |
| Sensitivity Analysis in Bayesian networks | Adnan Darwiche | Chapter 16 of a UCLA course -- Learning and Reasoning with Bayesian Networks. Discusses the relationship between network parameters and queries. Explores how one can bound changes to queries in terms of changes to parameters; how one can change parameters to ensure some constraints on the results of queries; and how one can measure change to parameters so as to provide guarantees on the network robustness. | https://www.youtube.com/watch?v=S3sefsvWfDQ |
 | 04-2 Sensitivity Analysis Global | Jef Caers | Presentation at Leland Stanford Junior University about Sobol indices and regionalized sensitivity analysis | https://www.youtube.com/watch?v=vBuWB9WuFhA | 
 | Samo 2016 : Sobol' sensitivity analysis | Iooss Bertrand | Lecture at Université de La Réunion about Sobol' sensitivity analysis for stochastic numerical codes | https://www.youtube.com/watch?v=TvA1Cmmkg20 | 
 
 ## Software
 
 | Software | URL | Description |
 |----------|-----|-------------|
 | SAMIAM | http://reasoning.cs.ucla.edu/samiam/ | *Samiam* is a tool (in Java by UCLA) for modeling and reasoning with Bayesian networks with two main components: a graphical user interface and a reasoning engine. The GI lets users develop Bayesian network models, while the reasoning engine allows the execution of many tasks such as: classical inference; parameter estimation; time-space tradeoffs; sensitivity analysis; and explanation-generation based on MAP and MPE. ||
  | SHAP | https://github.com/slundberg/shap | Python module for SHAP values |
  | Scikit | https://scikit-learn.org/stable/inspection.html | Partial dependence plots and Permutation feature importance |
  | ELI5 | https://eli5.readthedocs.io/en/latest/ | Allows using ELI5 and LIME |
  | Yellowbrick | https://www.scikit-yb.org/en/latest/ | Support several visualizers. |
  | Alibi | https://docs.seldon.io/projects/alibi/en/latest/ | Provides several methods for explanability : Accumulated Local Effects, Anchor explanations, Contrastive Explanation Method (CEM), Counterfactual Instances, Counterfactuals Guided by Prototypes, Kernel SHAP, Integrated gradients, Linearity Measure, and Trust Scores |
