# <div align="center">Unfathomable?</div>

## Description:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Stumble upon a fine tuning that is unfathomable?

## Purposes:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I just happened to use a PEFT fine tuned model from my previous "First Fine Tuning LLM" project to infer this question "What is the capital of USA?"  Surprisingly, the model returned correct answer.  So, I tried it on the full fine turning model from the same project, but it did not give the right answer.  The same was true for the base model.

I then put together a small test dataset to run through three models.  The results are:

PEFT model got %77 

Full fine tuning model got %50   (the Washington or Washington, D. C. )

Base model got %27


## File Descriptions

- **`flant5_full.ipynb`**: A simple full fine-tuning for the Flan-T5 model lab in Jupyter Notebook

- **`flant5_peft.ipynb`**: A simple PEFT for the Flan-T5 model lab in Jupyter Notebook

- **`testing_full.ipynb`**:  Inferring Q/A test for full fine-tuning  model in Jupyter Notebook.

- **`testing_peft.ipynb`**:  Inferring Q/A test for PEFT model in Jupyter Notebook.

- **`testing_base.ipynb`**:  Inferring Q/A test for Flan-T5 base model in Jupyter Notebook.

## Contributors 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The scripts are based on the online class "Generative AI with Large Language Models" from Coursera.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ChatGPT-3.5 the coding machine!

## Project Attribution
    Model from Hugging Face: 
    - google/flan-t5-base

## Disclaimer

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This project is provided "as is" and without any warranty. Use it at your own risk. 
    





