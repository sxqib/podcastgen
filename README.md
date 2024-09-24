# PodcastGen 🎙️

PodcastGen is an innovative AI-powered tool that generates engaging two-speaker podcasts from text input or document uploads. Transform your ideas, articles, or research into lively audio conversations with just a few clicks!

## 🌟 Features

- Generate podcasts from text input or uploaded PDF/TXT files
- AI-powered script generation using Gemini API
- Two-speaker format for dynamic conversations
- Multiple language support with auto-detection
- Customizable voice selection for speakers
- High-quality text-to-speech using Edge TTS

## 🚀 Try It Out on Hugging Face
[![Open in HuggingFace Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue)](https://huggingface.co/spaces/saq1b/podcastgen)

## 🛠️ How It Works

1. **Input**: Provide text or upload a PDF/TXT file.
2. **Language Selection**: Choose a language or use auto-detect.
3. **Voice Selection**: Pick voices for each speaker from various options.
4. **AI Processing**: 
   - Gemini API generates an engaging podcast script.
   - TTS converts the script to natural-sounding speech.
5. **Output**: Download your generated podcast audio file.

## 🎛️ Customization

- **Voices**: Choose from a variety of voices for each speaker, including:
  - Andrew, Ava, Brian, Emma (English)
  - Florian, Seraphina (German)
  - Remy, Vivienne (French)
  - And more!

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/sxqib/podcastgen.git
   cd podcastgen
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

### Running the Application

1. Set your Gemini API key as an environment variable in either the `.env` file or by:
   ```
   export GEMINI_API_KEY='your-api-key-here'
   ```

2. Run the Gradio app:
   ```
   python app.py
   ```

## 👏 Acknowledgements

- NotebookLM for inspiring me to create this.
- Gemini API for powerful language processing
- Edge TTS for high-quality speech synthesis
- Gradio for the user-friendly interface

Happy podcasting! 🎉
