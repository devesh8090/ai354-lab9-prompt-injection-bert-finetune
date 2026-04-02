1. Take 100 samples that are labeled 1 from the training
https://huggingface.co/datasets/xTRam1/safe-guard-prompt-injection dataset and use
them as prompts to test 2 LLMs (any LLM will do). Record their responses and analyze
them.
2. Finetune a BERT model on the above training data to identify whether a prompt is
malicious (labeled 1) or benign (labeled 0). Report the performance on the test set of the
above dataset. (You can refer to
https://github.com/huggingface/notebooks/blob/main/examples/text_classification.ipynb
for BERT finetuning)
