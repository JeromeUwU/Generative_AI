# Generative_AI

This repository primarily focuses on the development of various generative AI models, encompassing text-to-speech, text-to-text, and speech-to-text functionalities, with the ultimate aim of creating a comprehensive personal AI vocal chatbot. All models will be trained using publicly accessible datasets from GitHub or Kaggle, utilizing Kaggle GPU or Colab GPU resources. The models will be based on freely available pretrained models. This repository will include a step-by-step tutorial to guide users in achieving the final Vocal Chat Bot.

## text-to-text 

The text-to-text model will be based on the pretrained FLAN-T5. For computational purposes, I used * *google/flan-t5-small* *, but better performance may be achieved with google/flan-t5-large. FLAN-T5 was introduced in the paper "Scaling Instruction-Finetuned Language Models." It's an enhanced version of T5 that has been fine-tuned across a mixture of tasks. You can find more information about it in the Hugging Face documentation https://huggingface.co/docs/transformers/en/model_doc/flan-t5.

The provided script is a simple fine-tuning script that can be improved and adapted for different large language models, such as GPT-4, ChatGPT, Llama, and more. The fine-tuned T5 model was trained for 15 epochs on a GPU P100 on Kaggle and took around 3 hours of training. The training dataset is sourced from the Bitext Customer Support LLM Chatbot Training Dataset, which is accessible from Hugging Face https://huggingface.co/datasets/bitext/Bitext-customer-support-llm-chatbot-training-dataset.

Implementation will be up soon 
