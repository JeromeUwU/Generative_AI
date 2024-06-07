# Generative_AI

This repository primarily focuses on the development of various generative AI models, encompassing speech-to-text, text-to-text and text-to-speech functionalities, with the ultimate aim of creating a comprehensive personal AI vocal chatbot. All models will be trained using publicly accessible datasets from GitHub or Kaggle, utilizing Kaggle GPU or Colab GPU resources. The models will be based on freely available pretrained models. This repository will include a step-by-step tutorial to guide users in achieving the final Vocal Chat Bot.

## speech-to-text


## text-to-text 

The text-to-text model will be based on the pretrained FLAN-T5. For computational purposes, I used **google/flan-t5-small**, but better performance may be achieved with **google/flan-t5-large**. FLAN-T5 was introduced in the paper "Scaling Instruction-Finetuned Language Models." It's an enhanced version of T5 that has been fine-tuned across a mixture of tasks. You can find more information about it in the Hugging Face documentation https://huggingface.co/docs/transformers/en/model_doc/flan-t5.

The notebook provided offers a basic fine-tuning algorithm that's versatile and can be enhanced and customized for various tasks and different large language models like GPT-4, ChatGPT, Llama, and others.The fine-tuned T5 model was trained for 15 epochs on a GPU P100 on Kaggle and took around 3 hours of training. The training dataset is sourced from the Bitext Customer Support LLM Chatbot Training Dataset, which is accessible from Hugging Face https://huggingface.co/datasets/bitext/Bitext-customer-support-llm-chatbot-training-dataset.

*Implementation will be up soon*

## text-to-speech

Text-to-Speech (TTS) involves generating natural-sounding speech from given text input. TTS models find applications in various speech-enabled systems like voice assistants or announcement systems, where converting text into speech resembling human voice is required.

The Hugging Face Hub offers over 1500 TTS models ready for use. Alternatively, models like WaveGlow or Tacotron2, available at the NVIDIA Tacotron2 GitHub repository, can be employed. However, in this case, I opted to create a custom TTS model based on the paper titled "Neural Speech Synthesis with Transformer Network."

The model was implemented and trained on Kaggle using a GPU P100. This approach allows for flexibility and customization in developing a TTS solution tailored to specific requirements.


*Theorie will be vulgarized*

*Implementation will be up soon* 
