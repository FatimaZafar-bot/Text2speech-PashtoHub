🗣️ Text ↔ Speech Pashto Hub

“AI-powered TTS & STT for Pashto — built using custom datasets and deep learning.”

📌 Project Overview

This project focuses on Pashto speech technology, implementing both:

  - Text-to-Speech (TTS) → Generate Pashto audio from text.

  - Speech-to-Text (STT) → Transcribe Pashto audio into text.

It is designed to bridge the gap for low-resource languages by experimenting with neural speech models using a custom dataset of 100 Pashto voice notes + JSON transcripts.

🛠️ Techniques & Methods :

📝 Speech-to-Text (STT)

- Model Used: Wav2Vec2.0 (transformer-based speech recognition)
- Framework: Hugging Face Transformers + PyTorch
- Training Data:  
     - Same 100 Pashto voice notes.
     - JSON file providing ground-truth transcripts.
- Procedure:
     - Audio files normalized & converted to .wav
     - Tokenizer built for Pashto script
     - Model fine-tuned for ~N epochs on dataset
- Output: Pashto transcription for unseen audio
