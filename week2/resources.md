# Week2 resources

## Generative AI Lifecycle
1. (Generative AI on AWS: Building Context-Aware, Multimodal Reasoning Applications)[https://www.amazon.com/Generative-AI-AWS-Multimodal-Applications/dp/1098159225/] - This O'Reilly book dives deep into all phases of the generative AI lifecycle including model selection, fine-tuning, adapting, evaluation, deployment, and runtime optimizations.

## Multi-task, instruction fine-tuning
1. (Scaling Instruction-Finetuned Language Models)[https://arxiv.org/pdf/2210.11416.pdf] - Scaling fine-tuning with a focus on task, model size and chain-of-thought data.

2. (Introducing FLAN: More generalizable Language Models with Instruction Fine-Tuning)[https://ai.googleblog.com/2021/10/introducing-flan-more-generalizable.html] - This blog (and article) explores instruction fine-tuning, which aims to make language models better at performing NLP tasks with zero-shot inference.

## Model Evaluation Metrics
1. (HELM)[https://crfm.stanford.edu/helm/latest/] - Holistic Evaluation of Language Models - HELM is a living benchmark to evaluate Language Models more transparently.

2. (General Language Understanding Evaluation (GLUE) benchmark)[https://openreview.net/pdf?id=rJ4km2R5t7] - This paper introduces GLUE, a benchmark for evaluating models on diverse natural language understanding (NLU) tasks and emphasizing the importance of improved general NLU systems.

3. (SuperGLUE)[https://super.gluebenchmark.com/] - This paper introduces SuperGLUE, a benchmark designed to evaluate the performance of various NLP models on a range of challenging language understanding tasks.

4. (ROUGE)[https://aclanthology.org/W04-1013.pdf]: A Package for Automatic Evaluation of Summaries - This paper introduces and evaluates four different measures (ROUGE-N, ROUGE-L, ROUGE-W, and ROUGE-S) in the ROUGE summarization evaluation package, which assess the quality of summaries by comparing them to ideal human-generated summaries.

5. (Measuring Massive Multitask Language Understanding (MMLU))[https://arxiv.org/pdf/2009.03300.pdf] - This paper presents a new test to measure multitask accuracy in text models, highlighting the need for substantial improvements in achieving expert-level accuracy and addressing lopsided performance and low accuracy on socially important subjects.

6. (BigBench-Hard - Beyond the Imitation Game)[https://arxiv.org/pdf/2206.04615.pdf]: Quantifying and Extrapolating the Capabilities of Language Models - The paper introduces BIG-bench, a benchmark for evaluating language models on challenging tasks, providing insights on scale, calibration, and social bias.

## Parameter- efficient fine tuning (PEFT)
1. (Scaling Down to Scale Up: A Guide to Parameter-Efficient Fine-Tuning)[https://arxiv.org/pdf/2303.15647.pdf] - This paper provides a systematic overview of Parameter-Efficient Fine-tuning (PEFT) Methods in all three categories discussed in the lecture videos.

2. (On the Effectiveness of Parameter-Efficient Fine-Tuning)[https://arxiv.org/pdf/2211.15583.pdf] - The paper analyzes sparse fine-tuning methods for pre-trained models in NLP.

## LoRA
1. (LoRA Low-Rank Adaptation of Large Language Models)[https://arxiv.org/pdf/2106.09685.pdf] - This paper proposes a parameter-efficient fine-tuning method that makes use of low-rank decomposition matrices to reduce the number of trainable parameters needed for fine-tuning language models.

2. (QLoRA)[https://arxiv.org/pdf/2305.14314.pdf]: Efficient Finetuning of Quantized LLMs - This paper introduces an efficient method for fine-tuning large language models on a single GPU, based on quantization, achieving impressive results on benchmark tests.

## Prompt tuning with soft prompts
1. (The Power of Scale for Parameter-Efficient Prompt Tuning)[https://arxiv.org/pdf/2104.08691.pdf] - The paper explores "prompt tuning," a method for conditioning language models with learned soft prompts, achieving competitive performance compared to full fine-tuning and enabling model reuse for many tasks.
