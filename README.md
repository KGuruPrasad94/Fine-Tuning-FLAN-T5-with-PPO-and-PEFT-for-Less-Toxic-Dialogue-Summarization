# **Exploring Dialogue Summarization with FLAN-T5**

## **Project Overview**

This project is an exciting dive into the world of Generative AI, where I focused on using the FLAN-T5 model for dialogue summarization. Along the way, I explored various techniques like prompt engineering, fine-tuning, and even reducing the toxicity of generated content. The journey also involved working with advanced methods like Parameter Efficient Fine-Tuning (PEFT) and Proximal Policy Optimization (PPO).

## **Notebooks Overview**

### **1. Generative AI Use Case: Summarize Dialogue**
- **Objective:** I wanted to see how different prompts can shape the output of the model and learned to craft inputs that guide the model towards better summaries.
- **Key Activities:**
  - Played around with zero-shot, one-shot, and few-shot inferences to understand their impact.
  - Experimented with prompt engineering to improve the quality of the summaries.

### **2. Fine-Tuning FLAN-T5 for Enhanced Summarization**
- **Objective:** I dove into fine-tuning to see how I could make the FLAN-T5 model even better at summarizing dialogues.
- **Key Activities:**
  - Conducted full fine-tuning of the model, which was a great hands-on experience.
  - Implemented PEFT using LoRA, making the process more resource-efficient.
  - Evaluated the results using ROUGE metrics and also did some human reviews to see how well the model performed.

### **3. Reducing Toxicity with PPO**
- **Objective:** This part was all about making the model's summaries less toxic by using reinforcement learning techniques.
- **Key Activities:**
  - Applied PPO in combination with Meta AI's hate speech reward model to guide the model in generating safer content.
  - Focused on evaluating and fine-tuning the model to ensure it produced more ethical and responsible outputs.
 
## **Technologies Used**

- **FLAN-T5 Model:** A powerful language model used for dialogue summarization.
- **Hugging Face Transformers:** The library used for implementing and fine-tuning the FLAN-T5 model.
- **Python:** The primary programming language used throughout the project.
- **PyTorch:** The deep learning framework used to fine-tune the model.
- **Meta AI's Hate Speech Reward Model:** Used to guide the model towards generating less-toxic outputs.

## **Key Concepts and Techniques Learned**
- **Prompt Engineering:** Learned how to create prompts that effectively guide the model's output.
- **Parameter Efficient Fine-Tuning (PEFT):** Implemented using LoRA to make the fine-tuning process more efficient
- **Proximal Policy Optimization (PPO):** Used reinforcement learning to improve the quality and ethics of the generated content.
- **Evaluation:** Employed ROUGE Metrics to assess how well the summaries matched reference texts, giving a quantitative measure of success.
