# LLM Model Chaabi

## Overview
This project demonstrates the use of a BERT-based language model for some task related to Chaabi. The model is hosted using Gradio for easy interaction. Alternatively all-MiniLM-L6-v2 model is also explored

## Usage

[Link to repository of Bigbasket_Chaabi](https://huggingface.co/spaces/VedantGitte/Bigbasket_Chaabi/tree/main)


You can access the hosted application through this [Basket](https://huggingface.co/spaces/VedantGitte/Bigbasket_Chaabi)

### Installation
Make sure to install the required libraries:
``transformers``, ``pandas``, ``gradio``, ``torch``


## File uses-

* **MiniLM_Model.ipynb**
   * Used ``sentence-transformers/all-MiniLM-L6-v2``
Embedding were created, but it couldnt upload to database completely to Pinecone.

* **BERT_Model.ipynb**
  * This file uses BERT Model to create vector embedding for the csv containing information of products of big basket and uplooads them to pinecone
  
* **index.ipynb**
  * This file contains the interface to take in the input, create vector embedding for input and returning the best output after matching with vector embedding uploaded to Pine Cone.

* **embeddings.pt**
  * This file contains vector embedding of csv which will further be uploaded to PineCone
    
* **BigBasket Chaabi**
  * This folder is uploaded on huggingface to host the project.
  * It contains ```app.py``` which is replica of index.py. It host the interfacce on Gradio
  
## Hosting the Application on Gradio
This project utilizes Gradio for hosting and interacting with the machine learning models. Gradio is a Python library that simplifies the process of creating user interfaces for machine learning models, making it easy to share and showcase your models with a wider audience.

You can access the hosted application through this public link-

[https://huggingface.co/spaces/VedantGitte/Bigbasket_Chaabi/](https://huggingface.co/spaces/VedantGitte/Bigbasket_Chaabi/)

### Space on hugging space
[https://huggingface.co/spaces/VedantGitte/Bigbasket_Chaabi/tree/main](https://huggingface.co/spaces/VedantGitte/Bigbasket_Chaabi/tree/main)



