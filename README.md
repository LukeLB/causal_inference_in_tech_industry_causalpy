# causal_inference_in_tech_industry_causalpy

Causal Inference in Python: Applying Causal Inference in the Tech Industry is an excellent book and guide written by Matheus Facure about how to get the most out of causal techniques in the tech industry. As a way of learning more about causal inference, PyMC, and the CausalPy library I've made this repo to store the ports of each chapter into CausalPy and PyMC.

The way I see it so far is: 
- Ch 1 - Introduces much of the core concepts and is light on code so has been left unchanged.
- Ch 2 - Focusses on core frequentist concepts like confidence intervals, null hypothesis testing, p-values these concepts aren't neeeded for th PyMC/CausalPy/Bayesian paradigm so don't require to be converted and it's beyond the scope of this project to introduce the core concepts of Bayesian stats, just read Stat Rethinking it'll be much better than anything I rehash.
- Ch 3 - Focusses on the idea of DAGs and how they relate to bias in causal inference. The code here doesn't need any translating.
- Ch 4 - Introduces linear regression has a tool in causal inference we can replicate much of this into PyMC or Bambi.
- Ch 5 - Deals with propensity score and uses a micture of linear and logistic regression which can be replicated in PyMC or Bambi.
- Ch 6/7 - Mixes traditional ML with causal infrence and applies tree based models (e.g., XGBoost). This could be replicated in with BART models but i don't know enough about those types of models to know whether that conversion is beneficial or useful.
- Ch 8 - Introduces the differnce in difference model type which can be implemented in CausalPy.
- Chp 9 - Dives into synthetic control which can be rewritten with CausalPy.
- Ch 10 - Applies geo and switch back experiments, there is an example of geo experiments in CausalPy but not sure about switch back experiments?
- Ch 11 - Final chapter looks at instrumental variables, there are docs on this in causalpy but looking at the chapetr it will likely be a mix of CausalPy/PyMC.
