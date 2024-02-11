# Chat-llamaindex RAG

This repository contains the code for the project "Chat-llamaindex-RAG" for the course "DataMining" at the University of Bologna.

## Description
The goal of this project is to create a multi-chatbot system that is able to answer user questions as well as to search for information on the user documents. The system is composed of 2 main component: the Chatbot and the LlamaIndex. The Chatbot is the main component of the system, it is able to answer user questions and to interact with the other components. The LlamaIndex is a search engine that is able to search for information on the user documents.

## How to run
To run the system you need to install the requirements and then:
1. Run the LlamaIndex server using the command `python3 main.py` in the backend folder
2. Run the Llamaindex frontend using the command `npm run dev` in the frontend folder

## Components
The models used in the project are:
- mistral (mistralai/Mistral-7B-Instruct-v0.1)
- zephir (HuggingFaceH4/zephyr-7b-beta)
- tinyllama (TinyLlama/TinyLlama-1.1B-Chat-v1.0)
- dolphin (cognitivecomputations/dolphin-2.6-mistral-7b-dpo)
- llama (meta-llama/Llama-2-7b-chat-hf)
- vicuna_3b_q4 (TheBloke/Wizard-Vicuna-30B-Uncensored-GPTQ:gptq-4bit-32g-actorder_True)
- llama_13B_4bit (TheBloke/Llama-2-13B-chat-GPTQ:main)

The vector database used in the project is **Milvus**.

The search engine used in the project is **LlamaIndex**.


## Authors
- [Andrea Zecca](https://github.com/AndreaZecca)
- [Antonio Lopez](https://github.com/elements72)
- [Matteo Vannucchi](https://github.com/MatteoVannucchi0)
- [Stefano Colamonaco](https://github.com/StefanoColamonaco)