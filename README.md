# Generative_AI

This repository primarily focuses on the development of various generative AI models, encompassing text-to-speech, text-to-text, and speech-to-text functionalities, with the ultimate aim of creating a comprehensive personal AI vocal chatbot. All models will be trained using publicly accessible datasets from GitHub or Kaggle, utilizing Kaggle GPU or Colab GPU resources. The models will be based on freely available pretrained models. This repository will include a step-by-step tutorial to guide users in achieving the final Vocal Chat Bot.

## text-to-text 

The text to text model will be based on pretrained FLAN-T5 for computational purpose I used google/flan-t5-small but better performence may be achieve with google/flan-t5-large 
FLAN-T5 was released in the paper "Scaling Instruction-Finetuned Language Models" - it is an enhanced version of T5 that has been finetuned in a mixture of tasks.https://huggingface.co/docs/transformers/en/model_doc/flan-t5

The script provided is a simple fine tuning script that can be improve and adapt for different Large Language Models (like GPT-4,ChatGPT,Llama, and More) the fined tuned t5 model was run for 15 epochs on GPU P100 on Kaggle and took around 3 hours of training, the training set comes from Bitext Customer Support LLM Chatbot Training Dataset. from the huggingfaces accesible here https://huggingface.co/datasets/bitext/Bitext-customer-support-llm-chatbot-training-dataset.

Implementation will be up soon 
