# 🚀 Colab AI 音声認識 & 一括翻訳システム

**OpenAI Whisper** と **Google Gemini 3.1 Pro** を統合した、高性能な動画文字起こし・翻訳ソリューションです。高精度な字幕と自然な口語翻訳を必要とするクリエイターや開発者に最適です。

## 🌟 特徴
- **クラウド計算**: Google Colab の GPU 資源を活用し、ローカル PC の負荷を軽減。
- **モジュール分離**: 「文字起こし」と「翻訳」を独立させ、柔軟なワークフローを実現。
- **プロ級の AI 翻訳**: Gemini 3.1 Pro による「ベテラン教師」スタイルの自然な日本語翻訳。
- **ハルシネーション抑制**: Whisper 特有の繰り返し（跳ね返り）現象を自動的にフィルタリング。

## 🛠️ ツール紹介
### 1. 🎬 [1_Whisper_Transcription_Hub.ipynb]
YouTube URL やローカルファイルに対応した高精度文字起こしワークステーション。自然な改行処理と校正 UI を内蔵。

### 2. 🌐 [2_Gemini_Batch_Translator.ipynb]
AI 搭載の独立型翻訳ツール。複数の SRT ファイルの一括処理とリアルタイムログ表示に対応。

## 🚀 クイックスタート
1. [Google AI Studio](https://aistudio.google.com/app/apikey) で Gemini API キーを無料で取得。
2. 各ノートブックの「Open in Colab」ボタンをクリックして実行。
3. 文字起こしを行う際は、ランタイムを **T4 GPU** に設定してください。
