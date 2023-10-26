# Hate Speech is all you don't need!

## This project is part of a module at UZH called 'Essentials in Text and Speech Processing'

## Abstract
The rise of social media platforms, empowering individuals to voice their feelings and opinions, is causing a huge problem with online hate speech and offensive language, threatening the well-being of online communities. While Machine learning models have been instrumental in detecting such hate speech, they remain vulnerable to subtle manipulations, such as character swaps or word replacements. Most existing works focus on how to optimize attacks on known models such as the BERT or RoBERTa model. However, there is less work providing an overview of different hate speech models under different attacks. In this work, we will train the RoBERTa model using adversarial training and evaluate the robustness using different adversarial attacks. The findings suggest that adversarial training can lower the attack success rate. However, overfitting to certain attacks can lead to harm to the overall robustness of a model. 

## Files
Following files are included in this repo:

[The initial training of the pretrained RoBERTa Model on the hate speech dataset](https://github.com/Mariinja/NLPHateSpeech/blob/main/inital_hate_speech_model_training.ipynb) 

[Adversarial attacks on the model](https://github.com/Mariinja/NLPHateSpeech/blob/main/adversarial_attacks.ipynb)

[Adversarial training on the model](https://github.com/Mariinja/NLPHateSpeech/blob/main/adversarial_training.ipynb)

[Adjusted trainer from textattack for our project](https://github.com/Mariinja/NLPHateSpeech/blob/main/trainer.py)

## Authors
Marinja Principe, Melanie Salzer, Alain Küng
