# Multilingual-Translation-and-Code-Generation-System-Using-Transformer-Models
This project is under progress as the major project for the 8th semester under my degree program. The aim is to train a LLM in Indian languages such that the translations are context accurate rather than just grammatically accurate. This helps to understand the tone and setting of a statement or paragraph and also helps understand the slang easily.
## Dataset
We use the Samanantar English–Hindi corpus:
https://huggingface.co/datasets/ai4bharat/samanantar

The dataset is loaded directly using:
datasets.load_dataset("ai4bharat/samanantar", "hi")
