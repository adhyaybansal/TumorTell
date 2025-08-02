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


------------------------------------------------------------------------------------------------------------------------
ScreenShots - 

![a6d58c0d0e534c7eb81404004433c274](https://github.com/user-attachments/assets/6d323669-378d-48ad-b8fd-f455ab31b6ab)
![825b3597e08d41bbafab2933ef70588f](https://github.com/user-attachments/assets/c75b3199-fce8-463f-834d-0a51a8a9a0bb)
![60ce4460ce904ab7aabc7350859ac5cc](https://github.com/user-attachments/assets/0b64f058-8e3f-4608-a634-42cd99f19990)
![38bbcfee896447b2b2adeb5e1e314e5c](https://github.com/user-attachments/assets/e89e81c9-df5e-4728-973b-b6818400e62b)
![7fcfdbad31734f629b7187ebaab647f6](https://github.com/user-attachments/assets/75b9fa69-5f7d-4d21-bc25-eb5d7c481f7e)
![0b288f620f4245daa36a630ab81f3e0f](https://github.com/user-attachments/assets/8fff7e20-f2dd-4078-88c6-7fa4579d4595)
![be8634a3483c4e08a991afcdec967eb7](https://github.com/user-attachments/assets/70f06cd5-600c-4269-b099-7f5f658cf7c2)
![b65eeca656014186af3946c2f8215fb0](https://github.com/user-attachments/assets/5c6db937-1700-4a32-8d1b-deef29e16125)




