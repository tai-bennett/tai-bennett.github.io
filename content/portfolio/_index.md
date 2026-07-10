---
title: "Portfolio"
description: "Machine Learning and Data Science Projects"
---

# Portfolio
The following consists of a collection of my work relevant to machine learning and data science. These project were done as independent projeccts or in collaboration with others at the University of Arizona.
<!-- This is the table of contents -->
<a href="#uplift-modeling" class="button research">Uplift Modeling</a> 
<a href="#production-ml-project-template" class="button research">ML Project Template</a> 
<a href="#chaos-in-lstms" class="button research">Dissertation</a> 

## Uplift Modeling 
A crucial step for marketing data analysis is the switch from predictive to causal machine learning. Marketing conversion is far less important than uplift (this increase in conversion probability when targeted an advertisement). However, we cannot observe both treatment and control conversion results for each customer. This is where causal uplift modeling comes in. This project trains uplift meta-learners on the criteo uplift dataset and create actionable policy from said models using uplift calibration via isotonic regression and policy validation. Additional features include; config driven model selection for easy experimentation, mlflow, optuna, uv and kedro. Find more at [(github)](www.github.com/tai-bennett/uplift_modeling)
## Production ML Project Template 
In the current state of data science, it is becoming more crucial that data scientist take on responsibilities of machine learning engineers. Stepping away from notebooks, dockerizing, system monitoring and governance are necessary for implementing sustainable ml systems. This project is a template for a machine learning project that can be immediatly put into production. It leverages minio for artifact storage, postgresql for logging, mlflow, optuna, docker and fastapi. Find more at [(github)](www.github.com/tai-bennett)
## Chaos in LSTMs
My dissertation is titled *Computer-Assisted Proofs of Chaos in the Long Short-Term Memory Model*. When the input sequence of an LSTM model is held constant as the zero sequence, the rsulting RNN can be viewed as a discrete dynamical systems on the hidden states and cell states of the network. In this setting, the LSTM model can be shown to have observable chaos in the form of absolutely continuous invariant measures. Furthermore, this occurs for a positive measure set of parameters/weights of the LSTM. This implies that there is a nonzero probability of the chaotic LSTM models appearing after training. Furtherwork on this subject includes improving these proofs and leveraging this deterministic chaos as a generative model.
