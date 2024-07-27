# Voicera: A Text-to-Speech Model

"Voicera" is a text-to-speech (TTS) model designed for generating speech from written text. It uses a GPT-2 type architecture, which helps in creating natural and expressive speech. 
The model converts audio into tokens using the "Multi-Scale Neural Audio Codec (SNAC)" model, allowing it to understand and produce speech sounds. 
Voicera aims to provide clear and understandable speech, focusing on natural pronunciation and intonation. It's a project to explore TTS technology and improve audio output quality.

## How It Works

1. **Data Preparation**: We use a dataset containing text paired with corresponding audio. The audio is tokenized using the Multi-Scale Neural Audio Codec (SNAC) model, which converts audio into a sequence of tokens that the model can process.

2. **Model Architecture**: Voicera uses a transformer-based architecture similar to GPT-2, which is adept at handling sequential data. This architecture allows the model to understand the nuances of language and generate coherent speech.

3. **Training**: The model is trained on a large dataset of paired text and audio tokens. After each epoch, the model's performance is evaluated to ensure the generated audio improves over time.




## Demo

Here are some samples of the current state of Voicera's outputs:

1. **Sample 1**: [Generated Audio](https://github.com/Lwasinam/voicera/blob/master/examples/base_txt10_0.wav)
2. **Sample 2**: [Generated Audio](link-to-audio-sample-2)
3. **Sample 3**: [Generated Audio](link-to-audio-sample-3)

## Getting Started

There are three models, We have the base model and two other finetuned on jenny and expresso datasets
The best of all currently is the Jenny finetune
Here are colab link to all 3 respectively
1. [Base Model](https://colab.research.google.com/drive/10nPKliRs1C3ofv2J16_HGDlmzfd-yBtj#scrollTo=r17orAuZ45Q2)
2. [Jenny-Finetune](https://colab.research.google.com/drive/1MSzGGqIhGYVCn76alsX9oBzwC4EtOQSR#scrollTo=Oz0DG-MtovBw)
3. [Expresso-Finetune](https://colab.research.google.com/drive/1wzwSOtpT1CpEMvbcjvvgEKQZoQa5bX2p#scrollTo=YrBUwCNYmmUW&uniqifier=1)


