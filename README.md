1. Load dataset from Hugging Face and preprocess it to Llama-2 format.
2. Set up QLoRA, bitsandbytes, training and SFT parameters.
3. Perform PEFT with QLoRA to fine-tune in 4-bit precision (using quantization).
4. Load base LLM, and fine-tune.
5. Save model and test with question in dataset.
6. Reload model and merge it with LoRA weights and push to hugging face model hub for inferencing.

Project Reference from https://github.com/krishnaik06, follow him for more interesting R&D work!
