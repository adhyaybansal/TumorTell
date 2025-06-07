🧠 TumorTell – Brain Tumor Detection, Saliency Mapping & LLM-Generated Reports
TumorTell is a powerful deep learning-based web application built using Streamlit that enables automated brain tumor detection from MRI scans. It not only classifies the type of tumor, but also highlights suspicious regions via saliency maps, and generates natural language medical reports tailored for doctors or patients using advanced Large Language Models (LLMs) like Gemini and LLaMA.

🚀 Features
🔍 Brain Tumor Classification
Predicts whether an uploaded brain MRI image contains one of the following:

Glioma

Meningioma

Pituitary tumor

No tumor

🧊 Saliency Map Generation
Visualizes the important regions in the MRI that the model focused on during prediction. The map helps explain "why" the model made its decision by highlighting potential tumor areas in light cyan overlays using gradient-based techniques (similar to Grad-CAM).

🧠 LLM-Based Medical Reports
Generates a concise, customized report based on the saliency map and model's prediction:

🩺 Doctor Mode: Professional terminology and diagnostic suggestions.

🧍 Patient Mode: Simple, everyday language with guidance on next steps.

🤖 Model Choices
Supports multiple models including:

Xception (Transfer Learning)

Custom CNN

Data-Augmented CNN

🧬 LLM Choices
Choose from:

Google Gemini 1.5 Flash

Groq LLaMA 3.2 Vision (Preview)

▶️ How to Run
Install dependencies (e.g., using pip install -r requirements.txt)

Make sure your .env file contains the required API keys

Place your model weights in the correct paths as expected in app.py

Then, in your terminal:

streamlit run app.py


⚙️ Tech Stack
Frontend/UI: Streamlit

Modeling: TensorFlow / Keras

Image Processing: OpenCV, NumPy

LLMs: Google Gemini 1.5, Groq LLaMA Vision

Visualization: PIL, Plotly

🌐 Ideal Use-Cases
Medical diagnosis support for radiologists and neurologists

Patient-friendly explanations in telemedicine or health-tech platforms

Educational tool for medical students to interpret MRI + AI results

📌 Note
This app is not a replacement for professional medical advice. It is intended for educational and research purposes only.

