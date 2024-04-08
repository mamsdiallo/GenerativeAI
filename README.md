# GenerativeAI
Projects in Generative AI
## Chapter 1: Generative AI Fundamentals
### Project: Apply Lightweight Fine-Tuning to a Foundational Model
File: LightweightFineTuning_Mdiallo.ipynb
Executed on Google Colab

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

Resources on Fine-tuning with GPT2: 
Source: https://drlee.io/fine-tuning-gpt-2-for-sentiment-analysis-94ebdd7b5b24 

Resource on displaying information on GPU within Google Colab
Source: https://colab.research.google.com/drive/13dZVYEOMhXhkXWfvSMVM1TTtUDrT6Aeh?usp=sharing

Resource realted to 4-bit quantization
Source: https://huggingface.co/blog/4bit-transformers-bitsandbytes


