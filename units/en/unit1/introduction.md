# Introduction to Instruction Tuning

This module will guide you through instruction tuning language models. Instruction tuning involves adapting pre-trained models to specific tasks by further training them on task-specific datasets. This process helps models improve their performance on targeted tasks. 

In this module, we will explore two topics: 1) Chat Templates and 2) Supervised Fine-Tuning.

## 1️⃣ Chat Templates

Chat templates structure interactions between users and AI models, ensuring consistent and contextually appropriate responses. They include components like system prompts and role-based messages. For more detailed information, refer to the [Chat Templates](./chat_templates.md) section.

## 2️⃣ Supervised Fine-Tuning

Supervised Fine-Tuning (SFT) is a critical process for adapting pre-trained language models to specific tasks. It involves training the model on a task-specific dataset with labeled examples. For a detailed guide on SFT, including key steps and best practices, see the [Supervised Fine-Tuning](./supervised_fine_tuning.md) page.

## Exercises

For hands-on practice, please refer to the [exercises page](./exercises.md).

## References

- [Transformers documentation on chat templates](https://huggingface.co/docs/transformers/main/en/chat_templating)
- [Script for Supervised Fine-Tuning in TRL](https://github.com/huggingface/trl/blob/main/examples/scripts/sft.py)
- [`SFTTrainer` in TRL](https://huggingface.co/docs/trl/main/en/sft_trainer)
- [Direct Preference Optimization Paper](https://arxiv.org/abs/2305.18290)
- [Supervised Fine-Tuning with TRL](https://huggingface.co/docs/trl/main/en/tutorials/supervised_finetuning)
- [How to fine-tune Google Gemma with ChatML and Hugging Face TRL](https://www.philschmid.de/fine-tune-google-gemma)
- [Fine-tuning LLM to Generate Persian Product Catalogs in JSON Format](https://huggingface.co/learn/cookbook/en/fine_tuning_llm_to_generate_persian_product_catalogs_in_json_format) 