# Birlasoft-NLP


## Objective.

1. Research on Open Source LLMs - Falcon/MPT/Llama etc
2. Study LangChain
3. Study how to fine tune LLMs - see LORA framework
4. Pick variant based on:
    -  a. Size (First smaller variant e.g. 7b, then later larger 30b-e.g. Falcon-7b followed by Falcon-30B-b)
    -  b. Training mechanism: Instruction preferred, Completion may not meet our need (e.g. MPT-30B-Instruct)
5. POC: Two main tracks:
    -  a. Finetuning: Fine tune using "corporate" data (we will use dummy data and build framework)
    -  b. ReAct framework: Thought -> Reasoning -> Action - iterative
1. Implement a Proof of Concept (POC) with two main tracks:
   - a. Finetuning: Fine-tune the selected LLM using "corporate" data (dummy data will be used initially).
   - b. ReAct Framework: Explore the Thought -> Reasoning -> Action iterative framework using the LLM.

## LLM

1. bloom-1b

## Main Libraries
1. langchain

##Frameworks
1. LoRA

## High Level Process/pusedo code
- Document loading (from pdf, txt,word etc.)
- Document embedding, using LLM embeddings
- Train the retrival model
- query the document

## Results
