# Expanding-NLLB-200-to-Bhili-Fine-Tuning-Meta-s-Multilingual-Model-for-an-Underrepresented-Language
Welcome to the Hindi-Bhili Translation Model repository! This project focuses on extending Meta's No Language Left Behind (NLLB-200) multilingual translation model to support Bhili, a low-resource language spoken by millions in western India (primarily in Rajasthan, Gujarat, Madhya Pradesh, and Maharashtra). 
As a machine learning researcher specializing in natural language processing (NLP) and neural machine translation (NMT), I've built this based on my extensive work with models like NLLB, mT5, and techniques such as supervised fine-tuning (SFT), direct preference optimization (DPO), and custom tokenization. The pipeline includes training a SentencePiece tokenizer on Bhili data, integrating it with NLLB-200's distilled 600M-parameter variant, fine-tuning on a parallel Hindi-Bhili dataset, and evaluating with metrics like BLEU, CHRF2, ROUGE, and METEOR.

This is version 1.0 of the project. Future iterations may incorporate larger datasets, RLHF/DPO for preference optimization, and support for bidirectional translation or additional low-resource languages.

Key motivations:

Empower underrepresented languages in AI.

Support applications in education, healthcare, and cultural documentation for Bhili speakers.

Demonstrate scalable fine-tuning for low-resource NMT.

If you're working on NLP for Indian languages, model fine-tuning, or low-resource translation, this repo provides a practical starting point. Feel free to fork, contribute, or adapt it!

Features
Custom Tokenizer: Trained specifically on Bhili text to handle unique vocabulary and Devanagari script nuances.

Model Fine-Tuning: Adapted NLLB-200 for Hindi-to-Bhili translation with mixed precision, gradient accumulation, and learning rate scheduling.

Evaluation Suite: Scripts for computing BLEU, ROUGE, METEOR scores, plus visualizations for loss curves and translation length comparisons.

Inference Pipeline: Easy-to-use translation examples with Hugging Face's transformers library.

Data Processing: Handles CSV-based parallel datasets, tokenization, and train-test splits.

GPU Optimization: Designed for efficient training on systems like Google Colab or Kaggle with CUDA support.
