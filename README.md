
### 🩺 **Overview**

This project is an **AI-powered medical report analysis tool** that helps users understand complex medical PDFs in seconds. It allows users to upload a medical report (like a blood test), ask questions about it, and instantly get clear, human-like explanations — both in text and audio form.
Your app MedScope AI does 5 major things:

🩺 Analyze uploaded medical reports (PDF) using AI

🎧 Generate AI audio explanations (TTS)

💊 Recommend medicines using Groq AI API

🧠 Predict diseases using a trained Neural Network model

🩻 Analyze Chest X-rays (Normal vs Pneumonia) using a CNN model

⏰ Set medicine reminders using Telegram alerts

---

### ⚙️ **How It Works (Step-by-Step)**

1. **PDF Upload:**
   The user uploads a **medicasl report in PDF format** through a simple web interface.

2. **Content Extraction:**
   The system reads and extracts text from the uploaded PDF using a **PDF processing library**.

3. **AI Analysis:**
   The extracted text is sent to a **Large Language Model (LLM)** that understands and explains medical terms.

   * The model interprets medical data, explains lab results, and answers user questions.
   * It can provide a full analysis even if the user doesn’t ask a specific question.

4. **Agent-Based Reasoning:**
   An **AI agent** acts as a virtual doctor. It reasons through the report and generates a structured, easy-to-understand explanation using a prompting framework.

5. **Response Generation:**
   The model’s answer is displayed neatly on the web page.
   It simplifies medical jargon into understandable language.

6. **Audio Output (Text-to-Speech):**
   The text explanation is automatically converted into speech using a text-to-speech engine so users can **listen** to the report summary.

7. **Interactive Interface:**
   The entire process happens in a **Streamlit web app** with a dark, modern design.
   Users can:

   * Upload a new report
   * View a preview of all PDF pages
   * Ask custom questions
   * Listen to or read the AI’s summary

8. **Privacy & Local Use:**
   The app doesn’t store user data — everything runs locally or securely through API calls.

---

### 💡 **Key Functionalities**

* Upload medical PDFs
* Extract and understand report data automatically
* Ask natural language questions about the report
* Get AI-generated explanations
* Listen to answers as audio
* Fast processing and interactive user experience

---

### 🧰 **Technology Used**

* **Streamlit** → Web interface
* **LLM (AI model)** → For understanding and explaining reports
* **PDF extraction library** → For reading report text
* **Text-to-Speech** → To generate audio
* **Environment variables** → For secure API key handling

| Step | What You Did                          | Why                            |
| ---- | ------------------------------------- | ------------------------------ |
| 1️⃣  | Downloaded real datasets              | Get diverse medical data       |
| 2️⃣  | Standardized column names             | Uniform structure              |
| 3️⃣  | Added “Disease” label                 | Enable classification          |
| 4️⃣  | Merged all datasets                   | Create one unified CSV         |
| 5️⃣  | Normalized numbers                    | Improve neural net performance |
| 6️⃣  | Saved as `merged_medical_dataset.csv` | Use for training later         |
