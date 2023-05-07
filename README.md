# Moroccan Pottery Plate AI Model B'Darija

**ArtisanAI** is a combination of two AI models: an NLP model that can process/translate text input in Darija language, and a diffusion model that can generate images based on that text input. The end result is a unique and customizable image that can be carved onto a Moroccan pottery plate.

## Table of Contents

- [Motivation](#motivation)
- [AI Tools](#aitools)
- [Challenges](#challenges)
- [Installation](#installation)
- [Contributing](#contributing)
- [Sources](#sources)


## Motivation

Moroccan pottery is a rich tradition that dates back centuries. Each pottery piece is unique, and often features intricate designs and patterns. However, carving these designs by hand is a time-consuming and labor-intensive process. This project aims to streamline the process by using AI to generate custom designs for Moroccan pottery plates.

## AI tools

### Models

To develop this project we use :

1. NMT [Neural Machine Translation]: approach to machine translation that uses neural network models to generate translations.
2. DreamBooth: technique to teach new concepts to Stable Diffusion using a specialized form of fine-tuning.
3. ControlNet: neural network architectures that can learn important features and patterns in the data. controlNet shown to achieve state-of-the-art performance.

### UI Library
- StreamLit

## Challenges

Some challenges that we faced during the development of this project include:

- **Language model accuracy:** Our NLP model needed to accurately understand and interpret Darija language, which can be difficult due to the lack of standardization and data.
- **Fine-tune LLMs:** We couldn't fine-tune LLMs (LLaMA and Alpaca) and train them on our dataset due to lack of computing power (RAM and GPU weren't enough), this lead us to use less complicated algorithms (NMT) just to continue working on the project and reach our goal.


## Installation

### Prerequisites

Before installing the project, you will need to have the following dependencies installed:

- Python 3.6 or higher
- PyTorch
- NumPy
- NLTK


### Installation

To install the project, follow these steps:

1. Clone the project from GitHub: `git clone https://github.com/abdellahelaaroub/ThinkAI-HARAWKAN.git`
2. Install the necessary dependencies: `pip install -r requirements.txt`


## Contributing

If you would like to contribute to the project, please follow these guidelines:

- Fork the project on GitHub
- Make your changes on a feature branch
- Submit a pull request with a detailed description of your changes and any relevant information
- Wait for feedback and approval from the project maintainers

## Sources
- [DreamBooth](https://colab.research.google.com/github/huggingface/diffusion-models-class/blob/main/hackathon/dreambooth.ipynb?authuser=1#scrollTo=b1a23ebf-cf7f-4acf-afd9-fabafa045b69) 

- [ControlNet](https://github.com/lllyasviel/ControlNet) 

- [HugginFace](https://huggingface.co) 
