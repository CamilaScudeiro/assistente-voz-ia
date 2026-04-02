## 🎤 Assistente de Voz com IA

Este projeto consiste no desenvolvimento de um assistente virtual com interação por voz, utilizando inteligência artificial para transcrição, processamento e resposta em linguagem natural.

A aplicação permite que o usuário envie um áudio com uma pergunta, que é convertida em texto por meio de um modelo de reconhecimento de fala. Em seguida, esse texto é processado por um modelo de linguagem, que gera uma resposta inteligente. Por fim, a resposta é convertida novamente em áudio, proporcionando uma experiência completa de interação por voz.

## 🚀 Tecnologias Utilizadas

- Whisper (Speech-to-Text)
- API da OpenAI (geração de respostas)
- gTTS (Text-to-Speech)
- Google Colab

## ⚙️ Como o projeto foi desenvolvido

O desenvolvimento foi realizado no ambiente do Google Colab, onde foram integradas diferentes etapas:

1. Captura ou upload de áudio
2. Transcrição do áudio para texto utilizando Whisper
3. Envio do texto para a API da OpenAI
4. Geração de resposta com base em inteligência artificial
5. Conversão da resposta em áudio utilizando gTTS

## 🧠 Uso de IA no desenvolvimento

Durante o desenvolvimento, foram utilizados prompts como apoio para construção e entendimento do código, auxiliando na integração das bibliotecas, na estruturação das funções e na resolução de erros.

Essa abordagem permitiu acelerar o aprendizado e aplicar conceitos práticos de desenvolvimento com inteligência artificial.

## 🎯 Objetivo

O objetivo do projeto é demonstrar a aplicação prática de IA em sistemas interativos, combinando processamento de linguagem natural e reconhecimento de voz para criar uma experiência de usuário mais natural e acessível.


This directory includes a few sample datasets to get you started.

*   `california_housing_data*.csv` is California housing data from the 1990 US
    Census; more information is available at:
    https://docs.google.com/document/d/e/2PACX-1vRhYtsvc5eOR2FWNCwaBiKL6suIOrxJig8LcSBbmCbyYsayia_DvPOOBlXZ4CAlQ5nlDD8kTaIDRwrN/pub

*   `mnist_*.csv` is a small sample of the
    [MNIST database](https://en.wikipedia.org/wiki/MNIST_database), which is
    described at: http://yann.lecun.com/exdb/mnist/

*   `anscombe.json` contains a copy of
    [Anscombe's quartet](https://en.wikipedia.org/wiki/Anscombe%27s_quartet); it
    was originally described in

    Anscombe, F. J. (1973). 'Graphs in Statistical Analysis'. American
    Statistician. 27 (1): 17-21. JSTOR 2682899.

    and our copy was prepared by the
    [vega_datasets library](https://github.com/altair-viz/vega_datasets/blob/4f67bdaad10f45e3549984e17e1b3088c731503d/vega_datasets/_data/anscombe.json).
