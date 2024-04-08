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
