**Hybrid Ultrasonic Image Diagnostics**
This project is an AI-based medical imaging system that classifies breast ultrasound images into Benign, Malignant, and Normal categories. It uses a hybrid deep-learning architecture and provides a user-friendly web interface built with Flask.

📌 Features
Upload ultrasound images for instant diagnosis
Hybrid deep-learning model (CNN + Transformer components)
Flask web interface for easy use
Works in Google Colab with Ngrok for public access

⚙️ Installation
Clone the repository:
git clone https://github.com/<your-username>/Hybrid-Ultrasonic-Image-Diagnostics.git
cd Hybrid-Ultrasonic-Image-Diagnostics
Install dependencies:
pip install -r requirements.txt
Run the Flask app:
python app.py
Open in browser
http://127.0.0.1:5000/

🧪 Usage
Upload a breast ultrasound image
The model predicts: Benign / Malignant / Normal
Displays probability scores

🛠 Technologies Used
Python
TensorFlow / Keras
Flask
NumPy
HTML / CSS

📦 Model
best_hybrid_weighted.h5
best_model.h5
best_transfer_vecalpha.h5
hybrid_model_export.h5
hybrid_model.keras
transfer_mobilenet_vecalpha.keras
