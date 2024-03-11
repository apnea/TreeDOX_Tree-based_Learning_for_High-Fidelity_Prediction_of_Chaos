# TreeDOX_Tree-based_Learning_for_High-Fidelity_Prediction_of_Chaos

This repository contains most of the code used in support of the paper "Tree-based Learning for High Fidelity Prediction of Chaos" ($`\textcolor{red}{\text{INSERT DOI}}`$), with the exception of code ran on the [RIT Research Computing cluster](https://www.rit.edu/researchcomputing/) for ease of reproducibility. I will do my best to update this repository when I have time, but please [reach out if you have questions](mailto:amg2889@rit.edu).


# Introduction
TreeDOX (**Tree**-based **D**elay **O**verembedded e**X**plicit memory learning of chaos) is a tree-based alternative to neural network based methods for model-free forecasting of chaotic systems, such as Recurrent Neural Networks (RNN), Long Short-Term Memory (LSTM), Reservoir Computing (RC), and Next-Generation Reservoir Computing (NG-RC). While these recurrent networks are able to implicitly capture fading short-term memory of a system, TreeDOX uses time delay overembedding to mimic this ability. Time delay overmbedding is a time delay embedding with higher embedding dimension that that suggested by Floris Takens, which allows for more accurate modeling of nonstationary systems. TreeDOX uses Extra Tree Regression (ETR) as the tree-based regression model, as it shares the resilience of its cousin, Random Forests (RF), but with faster training and less bias. We apply feature reduction to increase both training speed and generalizability of the model. See ($`\textcolor{red}{\text{INSERT DOI}}`$) for more details including the method by which we use training data to prescribe hyperparameter values, eliminating the need for expensive hyperparameter tuning.

<p align="center">
  <img src="https://github.com/amg2889/TreeDOX_Tree-based_Learning_for_High-Fidelity_Prediction_of_Chaos/assets/60440354/473e7fb1-25dd-43d4-9dff-08fdac2f6b17">
</p>

<p align="center">
  <img src="https://github.com/amg2889/TreeDOX_Tree-based_Learning_for_High-Fidelity_Prediction_of_Chaos/assets/60440354/de6c7d55-b1d5-4422-adae-3b7a99cd9d91">
</p>
