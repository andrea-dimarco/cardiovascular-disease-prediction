# Cariovascular Disease Prediction (2022)
In this project we analyzed patient medical and personal data to create a trajectory of events and try to predict whether the patient is going to have a cardiovascular disease in the next six months. We modeled a number of approaches both in the system architecture and the patient's trajectory definition, including PubMedBERT encoding, LSTM architecture, time-sennsitive and non time-sensitive trajectory definitions, Transformer architecture and Bayesian Optimization on the Transformer architecture with no Positional Encoding.

We concluded that the best algorithm for this task is the Transformer model with no positional encoding since it focuses more on the events rather than the order of said events, thanks to the Attention Matrix mechanism.

Given the nature of the project we cannot share the original dataset.

More information can be found in the [report](./res/project-report.pdf).
