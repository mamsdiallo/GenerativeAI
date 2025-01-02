# GenerativeAI
Projects in Generative AI
## Chapter 1: Generative AI Fundamentals
### Project: Apply Lightweight Fine-Tuning to a Foundational Model
Second Attempt:

File: **LightweightFineTuning_Mdiallo v2.ipynb** 

Changes from 1st attempt:
1. Replace the GPT2Tokenizer with AutoTokenizer
2. Replace the GPT2ForSequenceClassification with AutoModelForSequenceClassification
3. Using the AutoPeftModelForSequenceClassification instead of the AutoModelForSequenceClassification

Executed on Google Colab with V100 GPU

Comparison the PEFT results to the results from prior to fine-tuning

| Metric | Prior | PEFT |
| --- | ----------- | ----------- |
| eval_loss | 3.92986  | 0.55727 |
| eval_accuracy | 48.94% | 71.98% |
| eval_f1 | 32.17% | 71.77% |
| eval_precision | 23.96% | 72.41% |
| eval_recall | 48.94% | 71.98% |
| eval_runtime | 62.3483 | 108.3164 |

**We conclude the fine-tuning with PEFT is improving the performance**


First Attempt: NOT PASSED

File: LightweightFineTuning_Mdiallo.ipynb
Executed on Google Colab with L4 GPU

Comparison the PEFT results to the results from prior to fine-tuning

| Metric | Prior | PEFT |
| --- | ----------- | ----------- |
| eval_loss | 4.50913  | 0.5589 |
| eval_accuracy | 51.06% | 73.04% |
| eval_f1 | 34.51 % | 72.91% |
| eval_precision | 26.07% | 73.29% |
| eval_recall | 51.06% | 73.04% |
| eval_runtime | 102.1865 | 136.8249 |


We conclude the fine-tuning with PEFT is improving the performance.

### Resources related to chapter 1
Resources on Fine-tuning with GPT2: 
Source: https://drlee.io/fine-tuning-gpt-2-for-sentiment-analysis-94ebdd7b5b24 

Resource on displaying information on GPU within Google Colab
Source: https://colab.research.google.com/drive/13dZVYEOMhXhkXWfvSMVM1TTtUDrT6Aeh?usp=sharing

Resource realted to 4-bit quantization
Source: https://huggingface.co/blog/4bit-transformers-bitsandbytes

## Chapter 2: Large Language Models (LLMs) & Text Generation
### Project: Build Your Own Custom Chatbot

File: Chatbot_project_MDI.ipynb (here: https://github.com/mamsdiallo/GenerativeAI/blob/main/Chatbot_project_MDI.ipynb)

We conclude the model responds the differently meaning the dataset was appropriate for the task


## Chapter 3: Computer Vision and Generative AI
### Project: AI Photo Editing with Inpainting

File: **starterAI_PhotoEditingWithInpainting_MDiallo.ipynb** 

We conclude the inpaint is working perfectly.
