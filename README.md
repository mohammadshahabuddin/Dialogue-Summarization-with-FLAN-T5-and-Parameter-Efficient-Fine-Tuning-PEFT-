# Dialogue-Summarization-with-FLAN-T5-and-Parameter-Efficient-Fine-Tuning-PEFT

This repository demonstrates the process of enhancing dialogue summarization capabilities by fine-tuning the FLAN-T5 model, an instruction-tuned Large Language Model (LLM) from Hugging Face, using Parameter-Efficient Fine-Tuning (PEFT) techniques. The project evaluates the performance improvements achieved through PEFT by utilizing ROUGE metrics.

**Project Overview**

The objective of this project is to improve the summarization performance of the FLAN-T5 model on dialogue data without performing full fine-tuning. We utilized the "knkarthick/dialogsum" dataset from Hugging Face, which is structured as follows:

Training Set: 12,460 samples

Validation Set: 500 samples

Test Set: 1,500 samples

**Setup and Installation**

To replicate the experiments, install the following dependencies:

torch torchdata transformers datasets evaluate rouge_score loralib peft

**Parameter-Efficient Fine-Tuning (PEFT)**

PEFT focuses on updating a subset of parameters, reducing computational requirements while maintaining or improving performance. We employed Low-Rank Adaptation (LoRA) 

**Conclusion**

This project showcases the effectiveness of Parameter-Efficient Fine-Tuning in improving dialogue summarization tasks using the FLAN-T5 model. By updating a targeted subset of parameters, PEFT offers a resource-efficient alternative to full fine-tuning, achieving notable performance gains as evidenced by the ROUGE metrics.
