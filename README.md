# Colloquial-Translation-Model
Fine-tuned transformer model that converts English sentences into casual Hindi expressions. Based on Helsinki-NLP's opus-mt-en-hi and trained on a custom colloquial dataset.

Project Overview
- Created a custom English-to-Hindi colloquial parallel dataset.
- Fine-tuned the Helsinki-NLP/opus-mt-en-hi model using the Hugging Face Transformers library.
- Evaluated the model on unseen test data and assessed its translation accuracy.
- Prepared the model for deployment to support real-time colloquial translation and research applications.

Model Details
- Base Model: Helsinki-NLP/opus-mt-en-hi
- Framework: PyTorch & Hugging Face Transformers
- Training Data: Manually curated dataset of informal English-Hindi sentence pairs
- Training Type: Supervised fine-tuning with custom colloquial content

Intended Use

This model is best suited for:
- NLP research focused on informal or code-mixed language processing.
- Applications that require casual or conversational Hindi (e.g., chatbots, voice assistants).
- Language learning tools aiming to teach natural, everyday usage of Hindi.

Out of Scope
- Not recommended for formal translation use cases such as legal, medical, or academic content.
- May not handle region-specific dialects or heavily idiomatic expressions.
- Should not be used for offensive, misleading, or harmful language generation.

Hackathon Context: Sawit.AI

This model was built for the Sawit.AI Hackathon, with the goal of enhancing machine translation systems to understand and generate informal Hindi—common in podcasts, interviews, social media, and casual speech.
