# Integration of Removal-Based Explanations with LLaMA 3 7B Model

This repository demonstrates the integration of the [Removal-Based Explanations](https://github.com/iancovert/removal-explanations/tree/main) approach with the LLaMA 3 7B model for analyzing and understanding predictions.

## Overview

In this project, I utilized a dataset related to COVID-19 fake news classification to predict the veracity of news articles (true or false) using the LLaMA 3 7B model. The core objective of this work is to gain insights into which elements of the input prompts are influential in the model's predictions. 

To achieve this, I employed Removal-Based Explanations, a method detailed in the [paper](https://arxiv.org/abs/2011.14878). This method systematically removes or alters parts of the input to determine their impact on the model's output, providing a deeper understanding of the prediction process.
