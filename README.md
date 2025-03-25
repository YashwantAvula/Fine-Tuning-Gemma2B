# Fine-Tuning-Gemma2B Project Brief 

Fine-tuned Google’s Gemma 2B model using LoRA and QLoRA to improve mathematical reasoning on the Orca Math dataset. Achieved a 20% boost in Pass@1 accuracy on GSM8K while reducing memory usage via 4-bit quantization, enabling efficient training on limited hardware.

⸻

This project explores parameter-efficient fine-tuning of Google’s lightweight Gemma 2B language model to enhance its mathematical reasoning abilities. Leveraging LoRA (Low-Rank Adaptation) and QLoRA (Quantized LoRA), we fine-tuned the model on the Orca Math dataset and evaluated its performance using the GSM8K benchmark.

Highlights:
	•	Achieved a 20% improvement in Pass@1 accuracy post fine-tuning.
	•	Applied LoRA to transformer attention layers with rank=2 for efficient training.
	•	Used QLoRA for 4-bit quantized training, reducing memory usage by 3x.
	•	Trained on Google Colab Pro with 40GB A100 GPU using a resource-friendly setup.

 Technologies Used:
	•	Gemma 2B (2B parameter transformer model)
	•	LoRA and QLoRA (PEFT techniques)
	•	Orca Math Dataset (Microsoft)
	•	GSM8K Benchmark
	•	PyTorch, HuggingFace Transformers, BitsAndBytes

Goals:

To demonstrate how SLMs can be fine-tuned for high-accuracy tasks like math reasoning using minimal compute, enabling broader accessibility and deployment.

