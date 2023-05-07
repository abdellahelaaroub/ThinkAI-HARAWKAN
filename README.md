
# Moroccan Pottery Plate AI Model

**ArtisanAI** is a combination of two AI models: an NLP model that can process/translate text input in Darija language, and a diffusion model that can generate images based on that text input. The end result is a unique and customizable image that can be carved onto a Moroccan pottery plate.

## Table of Contents

- [Motivation](#motivation)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Sources](#sources)

## Motivation

Moroccan pottery is a rich tradition that dates back centuries. Each pottery piece is unique, and often features intricate designs and patterns. However, carving these designs by hand is a time-consuming and labor-intensive process. This project aims to streamline the process by using AI to generate custom designs for Moroccan pottery plates.

## Installation

### Prerequisites

Before installing the project, you will need to have the following dependencies installed:

- Python 3.6 or higher
- PyTorch
- NumPy
- NLTK
- Flask (if you plan on deploying the model to a web server)

### Installation

To install the project, follow these steps:

1. Clone the project from GitHub: `git clone https://github.com/your-username/moroccan-pottery-ai.git`
2. Install the necessary dependencies: `pip install -r requirements.txt`

### Configuration

If necessary, you can configure the project by modifying the `config.py` file. This file contains settings for the NLP model, the diffusion model, and other project parameters.

## Usage

### Command Line Interface

To use the project from the command line, follow these steps:

1. Navigate to the project directory: `cd moroccan-pottery-ai`
2. Start the Flask server: `python app.py`
3. Open a web browser and navigate to `http://localhost:5000`
4. Enter a Darija language text input into the provided text field and click "Generate Image"
5. View the generated image in the web page

### Examples

Here are some examples of Darija language text inputs that can be used to generate images:

- "بالمغرب الطين هو العنصر الأساسي لصنع الفخار"
- "أعطني صورة منزل مغربي تقليدي"
- "تصميم زهور مغربية على صحن الفخار"

## Challenges

Some challenges that we faced during the development of this project include:

- **Language model accuracy:** Our NLP model needed to accurately understand and interpret Darija language, which can be difficult due to the lack of standardization and data.
- **Fine-tune LLMs:** We couldn't fine-tune LLMs (LLaMA and Alpaca) and train them on our dataset due to lack of computing power (RAM and GPU weren't enough), this lead us to use less complicated algorithms (NMT) just to continue working on the project and reach our goal.
 


## Contributing

If you would like to contribute to the project, please follow these guidelines:

- Fork the project on GitHub
- Make your changes on a feature branch
- Submit a pull request with a detailed description of your changes and any relevant information
- Wait for feedback and approval from the project maintainers

## Sources
[Dreambooth](https://colab.research.google.com/github/huggingface/diffusion-models-class/blob/main/hackathon/dreambooth.ipynb?authuser=1#scrollTo=b1a23ebf-cf7f-4acf-afd9-fabafa045b69) 
[ControlNet](https://github.com/lllyasviel/ControlNet) 
[HugginFace](https://huggingface.co) 









link to colab : https://colab.research.google.com/drive/1sWyt8A1vgf202XP4hU7MiKWPc10lsBjt?usp=sharing
NLP collab : https://colab.research.google.com/drive/149JlcKd3nQQh_o6Qni_T0qqc22_lQnNq?usp=sharing 
