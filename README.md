# KenSho

*LLM-based Dream Interpretation for Better Diagnosis of Patients with Psychological Disorders and Trauma*

![KenSho](dream_logo.png)

## Overview

KenSho is an innovative project developed for the INNOVERSE 12 HACKATHON, aiming to enhance the diagnosis of psychological disorders through dream interpretation. By leveraging a large language model (LLM), we provide insightful interpretations of dreams that can assist healthcare professionals in understanding their patients' psychological states.

## Dataset

The dataset, named Dataset.txt, contains 64 dreams along with their corresponding interpretations. This textual dataset was manually created due to the absence of publicly available datasets specific to dream interpretation.

## Project Structure

- *app.py*: A Streamlit-based user interface program where users can input a dream description and receive an interpretation.
- *Dataset.txt*: Contains the manually compiled dreams and their interpretations.
- *dream_logo.png*: Logo for the KenSho model.
- *eval.py*: Contains code for evaluating interpretations of four dreams. We use a BERT model to encode the interpretations and calculate scores using cosine similarity to compare predicted and actual interpretations.
- *finetuned_llama_model.zip: This file contains all the necessary tokenizer and model requirements for the fine-tuned Llama 2 model (7 billion parameters). *Note: Model weights are not included due to memory constraints.
- *interpretation.ipynb*: A Jupyter Notebook that includes code for fine-tuning the Llama 2 model using our 64-dream dataset.

## Requirements

The requirements.txt file lists all the libraries and technologies used in this project. To install the necessary packages, run:
