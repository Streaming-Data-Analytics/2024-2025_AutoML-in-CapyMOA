# 2024-2025 AutoML in CapyMOA

Optional project of the [Streaming Data Analytics](http://emanueledellavalle.org/teaching/streaming-data-analytics-2023-24/) course provided by [Politecnico di Milano](https://www11.ceda.polimi.it/schedaincarico/schedaincarico/controller/scheda_pubblica/SchedaPublic.do?&evn_default=evento&c_classe=811164&polij_device_category=DESKTOP&__pj0=0&__pj1=d563c55e73c3035baf5b0bab2dda086b).

Student: **[To be assigned]**

## Background
Automated Machine Learning (AutoML) is a fast-growing area that aims to automate the selection and optimization of machine learning models. In Streaming Machine Learning (SML), AutoML becomes even more crucial, as models must continuously adapt to incoming data without the possibility of extensive retraining.

CapyMOA already includes AutoML capabilities, but there are alternative approaches implemented in River that could enrich the framework. This project aims to integrate two automatic model selection methods into CapyMOA: Successive Halving Classifier and Bandit Classifier.

## Goals and objectives
- Reproduce the AutoML notebook of CapyMOA to understand the current functionality of the library.
- Implement in CapyMOA two model selection methods present in River:
  - Successive Halving Classifier: progressive selection of the best model by iteratively eliminating those with inferior performance.
  - Bandit Classifier: multi-armed bandit-based strategy to dynamically select the best model at each received instance.
- Integrate these two approaches into CapyMOA and create an AutoML suite.
- Compare the new implementations with the AutoML tools already present in CapyMOA.
- Analyze performance in terms of accuracy, computational efficiency, and adaptability to changes in the data.

## Deliverable
At the end of the project, the student should deliver:
- Report with explanation of methodology, analysis of results, and comparison with existing implementations.
- Notebook with:
  - Reproduction of the CapyMOA AutoML notebook.
  - Implementation of the new model selection methods in CapyMOA.
  - Comparison of different approaches.

This project will help improve the capabilities of AutoML in CapyMOA by exploring new strategies for automatic pattern selection and providing a comparison with existing techniques.


