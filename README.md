# Fine-Tuned Llama 3.1 8B for Marketing Ad Evaluation

## Overview
This project fine-tunes the **Llama 3.1 8B** model to assess marketing campaigns. The model provides structured feedback on advertisements, evaluating factors such as **target audience, call-to-action effectiveness, incentives, brand positioning, and ethical considerations**. 

## Features
- **Fine-tuned on 1,500+ ads** from various industries and global markets.  
- **Evaluates marketing principles** based on a structured rubric.  
- **Improves ad assessment accuracy** compared to the base Llama 3.1 8B model.  
- **Provides actionable insights** to optimize advertisements.  

## Dataset
- **Source**: A curated dataset containing advertisements across different platforms and industries.  
- **Size**: 1,500+ ad examples.  
- **Annotations**: Ads labeled with key marketing criteria for effective training.  

## Model Training
- **Base Model**: Llama 3.1 8B.  
- **Fine-Tuning**: Used **LoRA** and **PEFT** for parameter-efficient tuning.  
- **Evaluation**: Assessed using a custom rubric focusing on marketing principles.  
- **Performance**: The fine-tuned model shows a **42.25% improvement** over the base Llama model.  

The Model can be found at huggingFace through: https://huggingface.co/CodingGPT/marketing_model or CodingGPT/marketing_model at hugging face
