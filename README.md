# Project Title
AI Model Evaluation Prototype

## Introduction

This python project uses two AI models (DistilBART and T5) from Huggingface to generate summaries using the CNN-Daily Mail datasets. It then uses the ROUGE metric to evaluate the summaries generated by each model. The reference is taken from the research paper mentioned below. In that research, authors evaluated GPT-3, BRIO, and T0.

## Paper Reference

This project is based on the following research paper:
- **Title:** [News Summarization and Evaluation in the Era of GPT-3](https://api.semanticscholar.org/CorpusID:252532176)
- **Authors:** [Tanya Goyal, Junyi Jessy Li, Gregg Durrett]
- **Published in:** [The University of Texas at Austin]

## Models on Huggingface 
DistilBART: 
https://huggingface.co/sshleifer/distilbart-cnn-12-6
T5:
https://huggingface.co/t5-small

## Files 

- List of dependencies
requirements.txt 
- Python notebook containing the project code
prototype.ipynb
- Summaries generated by DistilBART
distilbart_summaries.json
- Summaries generated by T5
t5_summaries.json

## Installation and Dependencies

To ensure compatibility and isolate project dependencies, it is recommended to use a virtual environment. You can create a virtual environment and install the required dependencies using the following steps:

1. Create a virtual environment (replace 'myenv' with your preferred environment name):

   ```bash
   python -m venv myenv

2. Activate the virtual environment:
    ```bash
    ON MAC and Linux: source myenv/bin/activate
    ON Windows: myenv\Scripts\activate

3. Dependencies: To run this project, you need to install the required dependencies. Use the following command: 
    ```bash
    pip install -r requirements.txt

# Project Owner
Jasmine Kabir 
