# Smart-Waste-Classifier

♻️ Smart Waste Classifier — AI for Sustainability

A Deep Learning-based waste classification system that identifies waste as Organic or Recyclable using image recognition.
This project supports Sustainable Development Goals (SDG-11: Sustainable Cities & Communities) by promoting smart waste management.

📌 Project Description

With the rising environmental concerns and improper waste management in urban areas, this project leverages AI + Sustainability to classify waste materials.
The system accepts an image of waste and predicts whether it belongs to:

Category	Meaning
🥬 Organic Waste	Biodegradable items like food waste, leaves
🔁 Recyclable Waste	Plastic bottles, glass, metals, paper, cardboard

This solution can be scaled for smart dustbins, recycling plants, municipal systems, etc.

✅ Features

🧠 Deep Learning model using MobileNetV2

📦 Classifies waste into 2 categories

📁 Trained on real waste images dataset

🌐 Streamlit web-based UI for predictions

📊 Model accuracy printed during training

🪶 Lightweight & beginner-friendly

🧠 Tech Stack
Technology	Usage
Python	Programming
TensorFlow / Keras	Deep Learning Model
MobileNetV2	Transfer Learning
Streamlit	Front-End UI
NumPy, Pillow	Image Processing
Jupyter/VS Code	Development
📂 Folder Structure
Smart-Waste-Classifier/
│── dataset/
│   ├── Organic/
│   └── Recyclable/
│── waste_classifier.py      # Model Training
│── test_model.py            # Testing Script
│── app.py                   # Streamlit UI
│── waste_classifier.h5      # Saved Model
│── README.md

⚙️ Installation & Setup
1️⃣ Install dependencies
pip install tensorflow streamlit numpy pillow scikit-learn matplotlib

2️⃣ Train the model
python waste_classifier.py

3️⃣ Test the model
python test_model.py

4️⃣ Run the UI
streamlit run app.py

📊 Output Example

Input: Image of plastic bottle

Output: Recyclable

Input: Banana peel

Output: Organic

🌱 Sustainability Impact

This project supports:

✅ Proper waste segregation

✅ Encouraging recycling

✅ Reducing landfill impact

✅ Smart-city automation concept

🔮 Future Enhancements

Add 3-class model: Organic, Recyclable, Non-Recyclable

Deploy as mobile app

Improve dataset size & accuracy

Real-time camera-based detection

👤 Author

Satyajit Pratihar
IT Student | Beginner in AI/ML | Sustainability Enthusiast 🌍
