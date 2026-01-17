#  Universal Cyber-Translator (NLP & Morse)

A sophisticated Natural Language Processing (NLP) application designed to bridge communication gaps between traditional languages, Gen-Z slang, and low-bandwidth Morse code. This project features a high-performance translation engine wrapped in a "Cyber-Security" themed user interface.

##  Overview
This project leverages Meta's **NLLB-200 (No Language Left Behind)** model to provide high-fidelity translations across 200+ languages, including Hindi and English. It integrates a custom **Gen-Z Slang Interpreter** and a **Morse Code Encoder**, making it a multi-generational communication tool.

## Key Features
* **AI-Powered Translation:** Uses Transformer-based models for accurate multi-lingual support.
* **Slang Integration:** A custom mapping layer to decode "Gen-Z" terminology for professional or standard contexts.
* **Cyber-Security UI:** A "Cyber-Cyan" and "Matrix-Dark" themed interface built with Streamlit.
* **Morse Code Utility:** Instant conversion for low-bandwidth communication or cryptographic-themed projects.

## Repository Structure
* `GenZ-Translator.ipynb`: **The Source of Truth.** Contains the full problem definition, data preprocessing, and model implementation.
* `app.py`: The Streamlit deployment script.
* `requirements.txt`: Necessary Python libraries (Transformers, Torch, Streamlit).
* `slang_dictionary.json`: Custom dataset for slang-to-standard mapping.

## Technical Stack
* **Language:** Python 3.10+
* **Libraries:** `transformers`, `torch`, `sentencepiece`, `streamlit`
* **Model:** `facebook/nllb-200-distilled-600M`

## Notebook Highlights (Evaluation Criteria)
The included `.ipynb` file covers the following as per submission requirements:
1.  **Problem Definition:** Tackling the digital language divide and modern dialect shifts.
2.  **Data Preparation:** Tokenization, UTF-8 normalization, and custom dictionary creation.
3.  **Real-world Motivation:** Enhancing cross-cultural communication and accessibility.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/Cyber-Translator-AI.git](https://github.com/your-username/Cyber-Translator-AI.git)
