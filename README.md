# 🩺 AI-Assisted Symptom Checker

An interactive AI-powered web app that allows users to:
- Input their symptoms and health profile
- Get possible conditions and safe first aid suggestions
- Ask follow-up questions through a conversational chatbot
- Export the conversation as a professional PDF report

Built using **Streamlit**, **LangChain**, and **Gemini Pro**.

---

## 🚀 Features
- 💬 Hybrid chat & form UX
- 🔄 Conversation memory using LangChain
- 📄 Downloadable PDF report with disclaimer
- 🌗 Dark/light mode toggle
- 👥 Health filters (age, diabetes, smoke, alcohol)
- 🤖 Few-shot prompting for accurate results

---

## 🛠️ Tech Stack
- Python 3.10+
- [Streamlit](https://streamlit.io)
- [LangChain](https://www.langchain.com/)
- [Google Generative AI](https://ai.google.dev/gemini-api/docs)
- ReportLab (PDF generation)

---

## 📦 Installation

```bash
git clone https://github.com/your-username/symptom-checker.git
cd symptom-checker
python -m venv .venv
source .venv/bin/activate  # or .venv\Scripts\activate on Windows
pip install -r requirements.txt
```

Create a `.env` file:
```bash
cp .env.example .env
```
And add your Google Gemini API key:
```
GOOGLE_API_KEY=your-api-key-here
```

---

## 🧪 Run the App
```bash
streamlit run app.py
```

---

## 📝 Example Inputs
- Age: 25–35
- Diabetes: No
- Smoker: Yes
- Symptoms: "Chest pain, shortness of breath"

---

## 📄 Example Output PDF
- Shows user name and symptom result summary
- Follow-up chat transcript
- Legal disclaimer on each page

---

## 🔒 Disclaimer
> This tool is for informational purposes only and not a substitute for professional medical advice. Always consult a qualified healthcare provider.

---

## 🙌 Acknowledgements
- Gemini API by Google
- LangChain community
- Streamlit open-source devs

---

## 📬 Contact
Made with ❤️ by Mukesh Anchuri
