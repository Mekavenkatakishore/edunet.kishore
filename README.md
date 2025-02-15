# edunet.kishore

**📸 Image-Capture & Captioning with BLIP**

This is a Streamlit-based web app that allows users to capture images via webcam and ask multiple questions about the image using the BLIP (Bootstrapped Language-Image Pretraining) model.
___
🚀 **Features**

✔️ Capture images directly from the webcam

✔️ Ask multiple questions about the captured image

✔️ Uses BLIP (Salesforce/blip-vqa-base) for image question answering

✔️ Provides AI-generated answers for each question

✔️ Built with Streamlit for an interactive UI
___

🏗️ **Tech Stack**

Python

Streamlit (for UI)

Hugging Face Transformers (BLIP model)

Torch (PyTorch for inference)

PIL (for image handling)

___
📦 **Installation**

1️⃣ **Clone the Repository**

git clone https://github.com/your-username/your-repo-name.git

cd your-repo-name

2️⃣ **Create a Virtual Environment** (Optional but Recommended)

python -m venv venv

source venv/bin/activate  # On macOS/Linux

venv\Scripts\activate  # On Windows

3️⃣ **Install Dependencies**

import streamlit as st

import torch

from PIL import Image

from transformers import BlipProcessor, BlipForQuestionAnswering

4️⃣ **Run the App**

streamlit run app.py
___

🚀 **Deploying on Streamlit Cloud**

Push your code to GitHub

Go to Streamlit Community Cloud

Click “New App” → Select your repository

Choose app.py as the main file

Click Deploy 🎉

Your app will be hosted online with a public URL!
____
📜 **Usage Guide**

Open the app

Capture an image using the webcam

Enter multiple questions about the image

Click “Get Answers” to receive AI-generated responses

Click “Clear” to reset questions
____
📌 **Future Enhancements**

 Support image upload along with webcam capture
 
 Improve answer accuracy with fine-tuning
 
 Add text-to-speech (TTS) for reading answers aloud
 ____

✨ **Contributors**

👤 Your Name – GitHub Profile
