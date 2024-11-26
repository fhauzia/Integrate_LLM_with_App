# 🌟 Integrate LLM with IBM Cloud 🚀
<p align="center">
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
  <img src="https://img.shields.io/badge/Anaconda-3670A0?style=for-the-badge&logo=anaconda&logoColor=white">
  <img src="https://img.shields.io/badge/IBM%20Cloud-005C8E?style=for-the-badge&logo=ibmcloud&logoColor=white">
  <img src="https://img.shields.io/badge/Streamlit-FF4B5C?style=for-the-badge&logo=streamlit&logoColor=white">
  <img src="https://img.shields.io/badge/License-MIT-yellowgreen?style=for-the-badge&logo=opensource&logoColor=white">
</p>

## 🔥 Overview

Welcome to the **Integrate LLM with IBM Cloud** project! This project demonstrates how to integrate and invoke **Large Language Models (LLMs)** hosted on **IBM Watsonx.ai** using Python 🐍. You'll learn how to leverage IBM's powerful machine learning services to generate text, answer questions, and process customer complaints with ease.


This guide will help you set up everything from the IBM Cloud account to executing Python code for interacting with LLMs using IBM's API. 💡

## 🛠 Prerequisites

Before you start, you'll need the following:

- **IBM Cloud Account** 🌐: Sign up for a free IBM Cloud account [here](https://cloud.ibm.com) if you don't have one yet.
- **API Key** 🔑: You need an IBM Cloud API Key to authenticate and access Watsonx.ai services.
- **Project ID** 🆔: Create a project on IBM Cloud to interact with Watsonx.ai and retrieve the **Project ID**.

## 📦 Requirements

Before you begin, ensure you have the following:

- **Python 3.10**
- **Anaconda** (for environment management)
- **IBM Cloud Account** (for Watson API access)
  

## 📝 Example Output

Once the script is executed, you will interact with the IBM Watson API, and the system will generate responses based on the prompts. Here are some example outputs that you might see:
   ```bash
 python demo_wml_api.py
---------------------------------------------------------------------------
Question/request: Write a paragraph about the capital of France.
Answer: Paris is the capital and largest city of France. Paris is situated on the left bank of the Seine river, at its confluence with the Marne river, and its historical centre extends from the Latin Quarter to the Eiffel Tower.
---------------------------------------------------------------------------
C:\Users\A1404VA\AppData\Local\Programs\Python\Python311\Lib\site-packages\ibm_watson_machine_learning\foundation_models\utils\utils.py:273: LifecycleWarning: Model 'meta-llama/llama-2-13b-chat' is in deprecated state from 2024-08-26 until None. IDs of alternative models: None. Further details: https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/fm-model-lifecycle.html?context=wx&audience=wdp
---------------------------------------------------------------------------
Prompt:
From the following customer complaint, extract 3 factors that caused the customer to be unhappy.
Put each factor on a new line.

Customer complaint:
I just tried to book a flight on your incredibly slow website.  All
the times and prices were confusing.  I liked being able to compare
the amenities in economy with business class side by side.  But I
never got to reserve a seat because I didn't understand the seat map.
Next time, I'll use a travel agent!

Numbered list of all the factors that caused the customer to be unhappy:

List of complaints:
1. Slow website
2. Confusing times and prices
3. Lack of understanding of the seat map
---------------------------------------------------------------------------
--------------------------Invocation with REST-------------------------------------------
Question/request: Write a paragraph about the capital of France.
Answer: Paris is the capital of France and its traditional seat of government. The city is the capital of the Île-de-France region, which includes most of the French population. Paris is the seat of the French parliament, the French government and the French Supreme Court.
