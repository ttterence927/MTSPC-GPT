# MTSPC-GPT
## Finetuning Pretrained GPT-2 for Dutch TTF Gas Imbalance Prediction: A Mixed Time Series Prediction and Classification Approach

## Abstract
While Large Language Models (LLM) have achieved significant success in
natural language processing (NLP) and computer vision (CV), their applic-
ation in time series analysis has been limited due to the lack of large-scale
training data. This thesis addresses this challenge by finetuning pre-trained
models from language or computer vision, trained on billions of tokens, for
time series analysis. This thesis evaluates the Frozen Pretrained Transformer
(FPT), which leverages the self-attention and feedforward layers of residual
blocks from pre-trained models. The paper introduces MTSPC-GPT, a novel
approach that focus on fine-tuning the pre-trained GPT2 model for multi-
task learning, specifically for mixed time series prediction and classification.
This approach enables the model to concurrently perform classification and
forecasting tasks. The study also explores various methods to enhance the
predictability of gas-related time series, such as the Dutch TTF Gas Balan-
cing Signal, by integrating external features like weather data, power fore-
cast data, temporal features, and technical indicators. The results indicate
that these pre-trained models can deliver comparable or even superior per-
formance on public time series classification datasets and the Dutch TTF
Gas Imbalance Dataset.

# Visualization of Gas Balancing Predictive Indicators

![Gas Balancing Predictive Indicators](visual2.PNG)

This visualization represents various predictive indicators for gas balancing. Each color in the image has a specific meaning related to gas balancing signals and predictions:

- **Blue**: Represents the Gas Balancing Signal.
- **Purple and Light Blue**: Denote the thresholds for Imbalance.
- **Green**: Indicates the Probability of Imbalance for the next 5-12 hours.
- **Dark Yellow**: Signifies the Prediction of Imbalance within the Hour.

- ![Forecast Indicators](visual.PNG)

This visualization represents next 1-5 hours forecast for gas balancing:

- **Dark Green**: Upper interval(95%).
- **Red**: 50% prediction.
- **Yellow**: Lower interval(5%).
