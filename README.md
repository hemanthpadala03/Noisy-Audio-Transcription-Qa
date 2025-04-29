# Noisy-Audio-Transcription-QA

This project focuses on enhancing noisy audio signals, performing transcription using ASR models, and extracting meaningful insights using NLP techniques like Keyword Extraction and Question Answering (QA).

## Project Overview

The pipeline consists of three major stages:
1. **Audio Super-Resolution**:  
   Upsample low-quality 2kHz audio signals to high-quality 16kHz using multiple interpolation techniques and deep learning models.

2. **Automatic Speech Recognition (ASR)**:  
   Transcribe the enhanced audio into text using pre-trained ASR models from Hugging Face.

3. **NLP Analysis**:  
   Perform Keyword in Context (KWIC) extraction and context-based Question Answering (QA) from the transcribed text.

---

## Repository Structure

| File | Description |
| :--- | :--- |
| `All models.ipynb` | Training and evaluation of various super-resolution models (Vanilla CNN, SE, CBAM, ESA variants). |
| `interpolation-methods.ipynb` | Implementation of traditional interpolation methods for audio upsampling. |
| `noisy-audio-transcription-and-nlp-analysis-with-qa.ipynb` | Full pipeline: Audio enhancement → Transcription → Keyword Extraction → Question Answering. |
| `outputs-comp.ipynb` | Comparison of outputs from different methods/models. |

---

## Key Features

- **Audio Enhancement**: Super-resolve noisy low-sampling-rate audio using lightweight encoder-decoder models.
- **ASR Transcription**: Use advanced pre-trained ASR models like Whisper and Wav2Vec2 for accurate speech-to-text conversion.
- **Keyword Extraction**: Extract keywords from the transcribed text using NLP libraries like NLTK and spaCy.
- **Question Answering**: Implement context-aware QA using Hugging Face transformer models.

---

## Technologies Used

- **Deep Learning**: PyTorch, TensorFlow
- **ASR**: Hugging Face Transformers (Whisper, Wav2Vec2)
- **NLP**: NLTK, spaCy, Hugging Face QA pipelines
- **Audio Processing**: Librosa, Soundfile
- **Visualization**: Matplotlib, Seaborn

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/hemanthpadala03/Noisy-Audio-Transcription-Qa.git
   cd Noisy-Audio-Transcription-Qa
