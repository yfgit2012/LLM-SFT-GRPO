# LLM fine-tuning with SFT+GRPO

LLM fine-tuning techniques have evolved rapidly to meet the growing demands of specialized AI applications.    

Supervised Fine-Tuning (SFT) has emerged as a powerful method to adapt pre-trained models to specific tasks or domains, leveraging labeled datasets to enhance performance on targeted objectives. Instruction tuning is a specialized fine-tuning technique that trains Large Language Models to better understand and follow natural language instructions through instruction-response paired datasets. This approach enhances models' ability to interpret diverse commands and execute tasks across different domains, improving zero-shot performance and response reliability.    

Concurrently, Reinforcement Learning (RL) approaches like Group Relarive Policy Optimization (GRPO) have gained traction for their ability to align language models with human preferences without the need for explicit rewards. GRPO, building upon earlier methods like PPO and DPO, uses preference data to guide the model towards generating more desirable outputs. The combination of SFT and GRPO represents a potent strategy for LLM optimization.    

By first using SFT to adapt the model to a specific domain or task, and then applying GRPO to fine-tune based on human preferences, you can create highly specialized models that not only perform well on targeted tasks but also align closely with user expectations and ethical considerations. This hybrid approach allows for more nuanced control over model behavior, potentially leading to AI systems that are both highly capable and more aligned with human values.

## Example 

Using OpenMathReasoning-mini dataset to post-train [Qwen3-4B-Base](https://huggingface.co/Qwen/Qwen3-4B) using [unsloth](https://github.com/unslothai/unsloth)

- [Notebook](https://github.com/yfgit2012/LLM-SFT-GRPO/blob/main/SFT_GRPO_unsloth.ipynb)   
- [Dataset](https://huggingface.co/datasets/unsloth/OpenMathReasoning-mini)   

## Reference

- [DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models](https://arxiv.org/abs/2402.03300)
- [Unsloth](https://unsloth.ai/)    


