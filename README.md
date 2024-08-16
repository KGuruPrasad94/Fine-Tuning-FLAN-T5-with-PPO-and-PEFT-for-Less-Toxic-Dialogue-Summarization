Project Overview

This project explores the use of Generative AI for dialogue summarization with the FLAN-T5 model. It covers various techniques including prompt engineering, full fine-tuning, Parameter Efficient Fine-Tuning (PEFT), and Reinforcement Learning with Proximal Policy Optimization (PPO) to enhance model performance and reduce toxicity.

Notebooks

1. Generative AI Use Case: Summarize Dialogue

	•	Objective: Explore the impact of different prompts on model output and apply prompt engineering techniques.
	•	Highlights:
	•	Compare zero-shot, one-shot, and few-shot inference.
	•	Experiment with FLAN-T5’s prompt templates.
	•	Adjust generative configuration parameters.

2. Fine-Tune FLAN-T5 for Enhanced Summarization

	•	Objective: Improve dialogue summarization through full fine-tuning and PEFT.
	•	Highlights:
	•	Full fine-tuning of FLAN-T5.
	•	Parameter Efficient Fine-Tuning (PEFT) using LoRA.
	•	Evaluation with ROUGE metrics and human review.

3. Fine-Tune FLAN-T5 with PPO for Less-Toxic Summaries

	•	Objective: Reduce toxicity in generated summaries using PPO and a hate speech reward model.
	•	Highlights:
	•	Set up and fine-tune with PPOTrainer.
	•	Evaluate toxicity levels and model performance.

Key Concepts and Techniques

	•	Prompt Engineering: Techniques used to optimize input prompts for generating specific outputs from a generative AI model.
	•	Parameter Efficient Fine-Tuning (PEFT): A technique to fine-tune models efficiently with fewer computational resources by only adjusting a subset of the parameters.
	•	Proximal Policy Optimization (PPO): A reinforcement learning algorithm used to optimize policies in large-scale AI models.
	•	ROUGE Metrics: A set of metrics used to evaluate the quality of summaries generated by comparing them to reference summaries.



