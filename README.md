# 🤖 Vision AI Suite – Multi-Domain Intelligent AI Assistants

Vision AI Suite is a collection of AI-powered intelligent assistants built using Python, Gradio, and Google Gemini AI.
These applications use image-based AI analysis to help users in Agriculture, Education, and Healthcare domains.

---

# 🌟 Projects Included

## 🌾 AgroVision AI – Smart Farming Assistant

AgroVision AI helps farmers analyze crop images and identify:

* Plant diseases
* Pest attacks
* Soil conditions
* Nutrient deficiencies
* Crop stress

### Features

* 🌿 Plant Disease Detection
* 🐛 Pest Detection
* 🌱 Soil Analysis
* 💧 Irrigation Advice
* 🧪 Fertilizer Suggestions
* 📊 Crop Health Monitoring

---

## 📚 EduVision AI – Smart Student Assistant

EduVision AI helps students understand educational content from uploaded images.

### Features

* 📝 Assignment Help
* ✍️ Handwritten Notes Explanation
* 📊 Diagram Explanation
* ➗ Math Problem Solving
* 🎯 Exam Preparation Assistance
* 📖 Simple Student-Friendly Learning Support

---

## 🏥 MedVision AI – Clinical Medical Assistant

MedVision AI assists doctors and medical students by analyzing medical images.

### Features

* 🩻 X-Ray Analysis
* 🧠 MRI/CT Scan Review
* 🧪 Lab Report Understanding
* 🩺 Skin Condition Review
* 📋 Clinical Suggestions

⚠️ Disclaimer:
MedVision AI is intended for educational and clinical assistance purposes only.
It does NOT provide final medical diagnosis.

---

# 🛠️ Technologies Used

* Python
* Gradio
* Google Gemini AI API
* Pillow (PIL)

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/Vision-AI-Suite.git
cd Vision-AI-Suite
```

---

## 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 📦 requirements.txt

```txt
gradio
google-genai
Pillow
```

---

# 🔑 Gemini API Configuration

Replace:

```python
api_key="YOUR_API_KEY"
```

Recommended secure method:

```python
import os
os.environ["GEMINI_API_KEY"] = "your_api_key"
```

---

# ▶️ Run the Applications

## 🌾 AgroVision AI

```bash
cd AgroVision
python app.py
```

---

## 📚 EduVision AI

```bash
cd EduVision
python app.py
```

---

## 🏥 MedVision AI

```bash
cd MedVision
python app.py
```

---

# 📸 How It Works

1. Upload an image
2. Select AI analysis mode
3. Add optional notes
4. Click Analyze
5. Receive AI-generated report

---

# 🚀 Future Improvements

## AgroVision

* Multi-language farmer support
* Weather prediction integration
* Crop recommendation system
* Real-time camera analysis

## EduVision

* OCR text extraction
* PDF upload support
* Quiz generation
* AI voice tutor
* Flashcard generation

## MedVision

* DICOM image support
* Medical report summarization
* Clinical chatbot
* Voice-enabled assistant

---

# ☁️ Deployment Platforms

You can deploy these applications on:

* Hugging Face Spaces
* Render
* Railway
* Gradio Hosting
