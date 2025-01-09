This repo contains Jupyter notebooks replicate the implementation of ClinicR:

Paper: http://arxiv.org/pdf/2403.04890
Code: https://github.com/ColdSeal/ClinicR/tree/main

1. **ClinicR**  
   Replicate ClinicR demo notebook with different models from HuggingFace.

2. **ClinicR_Ollama**  
   Replicate ClinicR demo notebook with different models served by Ollama locally.

3. **Assignment**  
Follow the algorithm described in the ClinicR paper, with the following modifications:
Download and use MedMCQA dataset for evaluation instead of the the MedQA dataset originally used in the paper
Use LLama3.2-1B instead of Llama-2-7b-chat-hf
Instead of training a verifier, use a prompting approach for the verifier: combine the MCQ approach to eliminate options created by ClinicR
---

