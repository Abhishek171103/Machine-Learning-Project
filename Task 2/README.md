## Text Generation using GPT-2 (Hugging Face Transformers)

This project uses a pre-trained GPT-2 model from Hugging Face to generate text from a custom prompt using different temperature values to demonstrate the impact on creativity and randomness.


## 📚 Model Used

- **GPT-2 (small)** from Hugging Face
- Library: `transformers`

## 🛠 Requirements

Install the required libraries before running:
- pip install transformers torch

## 🚀 How to Run

Run the Python script:
- python generate.py

The script will:
-Generate text from a prompt: "Once upon a time"
- Use top_k=50 and two temperatures: 0.7 and 1.0
- Save both outputs to generated_outputs.txt

## 🧪 Prompt & Parameters
- Prompt: Once upon a time
- Top-k sampling: 50
- Temperatures: 0.7 (coherent) and 1.0 (creative)
- Max Tokens: 50 (excluding prompt)

## 📂 Files Included
- generate.py – Main script for generation
- generated_outputs.txt – Generated text from GPT-2 at two temperature levels

## 📌 Notes

- Temperature 0.7 produces more consistent and coherent output.
- Temperature 1.0 generates more creative and diverse sentences.
