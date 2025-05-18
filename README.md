# 🗣️ Voice-Activated Information Service for Multiple Languages

This project is an intelligent voice-enabled chatbot that can:
- Scrape and analyze content from any website
- Answer questions based on the scraped content using OpenAI's GPT models
- Translate inputs and outputs across multiple languages
- Speak responses aloud using Text-to-Speech (TTS)
- Provide an intuitive interface using Gradio

All of this is built into a single Jupyter Notebook: `custom_chatbot.ipynb`.

---

## 🚀 Features

✅ **Web Scraping**  
Extract and clean text content from a given URL using `requests` and `BeautifulSoup`.

✅ **Multilingual Translation**  
Translate between multiple languages using `googletrans` and `deep_translator`.

✅ **Voice Output**  
Convert chatbot responses to speech using `gTTS`.

✅ **AI-powered Chat**  
Ask questions and get intelligent responses using OpenAI’s GPT model (`gpt-4o-mini`).

✅ **Interactive UI**  
Engage with the chatbot through a simple web interface powered by `Gradio`.

---

## 🧰 Tech Stack

- **Python**
- **OpenAI API** (`gpt-4o-mini`)
- **Gradio**
- **Google Translate** (`googletrans`, `deep_translator`)
- **Text-to-Speech** (`gTTS`)
- **Web Scraping** (`BeautifulSoup`, `requests`)
- **Voice Activation (TTS Output)**
- **Environment Config** (`python-dotenv`)

---

## 📁 File Structure

```
📦 Voice-Activated-Information-Service-for-Multiple-Languages
 ┣ 📄 custom_chatbot.ipynb
 ┣ 📄 README.md
 ┗ 📄 .env
```

---

## 📦 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/Voice-Activated-Information-Service-for-Multiple-Languages.git
cd Voice-Activated-Information-Service-for-Multiple-Languages

# Install required packages
pip install -r requirements.txt
```

If a `requirements.txt` is not available, install manually:

```bash
pip install openai gradio requests beautifulsoup4 googlesearch-python googletrans gtts deep_translator python-dotenv
```

---

## 🔑 API Key Setup

1. Create a `.env` file in the root directory:
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

2. Ensure your OpenAI key is active and has access to `gpt-4o-mini`.

---

## 🧪 How to Use

You can run the chatbot directly from the Jupyter Notebook:

```bash
jupyter notebook custom_chatbot.ipynb
```

Or convert it to a script if needed and run:

```bash
python custom_chatbot.py
```

The interface will open in your browser via Gradio. Enter a website URL, ask a question about its content, and hear the answer in your chosen language!

---

## 🎯 Use Cases

- Multilingual information retrieval
- Research assistant for global content
- Accessibility for visually impaired users
- Educational tools in native languages

---

## 📝 License

This project is licensed under the MIT License.

---

## 🙋‍♂️ Author

**Manu**  
GitHub: [Manudeep123](https://github.com/Manudeep123)

---

⭐ If you find this project useful, consider giving it a star!



MIT License. See `LICENSE` file for details.

## 🙋‍♂️ Author

- Manu
- GitHub: [Manudeep123](https://github.com/Manudeep123)



