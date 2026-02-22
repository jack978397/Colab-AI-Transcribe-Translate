# 🚀 Colab AI Transcription & Batch Translation System

A high-performance video transcription and translation solution leveraging **OpenAI Whisper** and **Google Gemini 3.1 Pro**. Designed for creators and developers who need high-precision subtitles and natural colloquial translations.

## 🌟 Highlights
- **Cloud Computing**: Utilize Google Colab's GPU (T4) for heavy transcription tasks.
- **Decoupled Modules**: Separate workflows for "Transcription" and "Batch Translation".
- **Professional AI Translation**: Context-aware translations using Gemini 3.1 Pro with a "Professional Teacher" persona.
- **Hallucination Filtering**: Advanced logic to filter out repetitive loops in Whisper's output.

## 🛠️ Tools
### 1. 🎬 [1_Whisper_Transcription_Hub.ipynb]
High-precision transcription workstation supporting YouTube URLs and local file uploads. Features natural sentence splitting and built-in proofreading UI.

### 2. 🌐 [2_Gemini_Batch_Translator.ipynb]
AI-powered standalone translator. Supports multiple SRT file batch processing with live progress logging.

## 🚀 Quick Start
1. Get your API Key from [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Open notebooks directly in Google Colab via the "Open in Colab" badge.
3. Set Runtime to **T4 GPU** for transcription.
