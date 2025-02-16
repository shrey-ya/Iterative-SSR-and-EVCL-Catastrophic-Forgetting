### Iterative SSR with EVCL for Catastrophic Forgetting on Text Based LLMs

We propose a novel framework integrating Elastic-Variational Continual Learning (EVCL) with an iterative feedback-enhanced SSR mechanism. While current EVCL approaches focus on neural networks in computer vision, we extend this concept to NLP, creating a pioneering system that iteratively refines SSR through feedback between a base LLM and an evaluator. Using quantized LLaMA 3 8B and 3.2 3B models, along with in-context learning, our method ensures high-quality synthetic datasets for continual learning. Initial experiments on low-resource settings show improved task retention compared to standard LoRA based Peft fine-tuning and vanilla SSR, showcasing its potential for real-world continual learning applications.

![Iterative SSR Architecture](report/Iterative-SSR-Architecture.png)
