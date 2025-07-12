# Label_GUI – Web-based Annotation System for Uroflowmetry Curves

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)  
![Built with Django](https://img.shields.io/badge/Built%20with-Django-blue.svg)

## 🚀 Overview

**Label_GUI** is a web-based graphical user interface for visualizing and annotating uroflowmetry curves. It is designed for researchers and clinicians to classify urine flow rate profiles into six medically relevant categories. The system supports interactive labeling, data storage, and export, and serves as a foundational tool for developing machine learning models.

<img width="1722" height="846" alt="Bildschirmfoto 2025-07-12 um 14 22 21" src="https://github.com/user-attachments/assets/4cbe6595-8125-4a60-8544-d367d525c250" />

Gastaccount: Tom
Passwort: 123456

## 🧩 Features

- 📈 **Interactive flow curve visualization** (time vs. flowrate)
- 🏷️ **Manual labeling with 6 classes:**
  - Normal
  - Interrupted
  - Staccato
  - Constrictive
  - Compressive
  - Super Voider
- 💾 Annotation and user log storage in a database
- 🔄 Comparison with model-predicted labels
- 📤 Export of labeled data
- 👥 Multi-user support and secure access

## 📦 Installation

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/label_GUI.git

# 2. Install Python dependencies
pip install -r requirements.txt

# 3. Run Django development server
python manage.py runserver

📁 Data Format

Uploaded CSV files should contain:
	•	Time samples: semicolon-separated time values (e.g., 0.0;0.2;0.4;...)
	•	Flowrate samples: semicolon-separated flowrate values
	•	Additional columns (optional):
	•	Qmax – maximal flowrate
	•	Qavg – average flowrate
	•	Voided volume, Flow time, Voiding time, etc.

🛠️ Tech Stack
	•	Backend: Django (Python)
	•	Frontend: HTML/CSS, JavaScript, Plotly.js, Bootstrap
	•	Database: SQLite (can be switched to PostgreSQL)

🎯 Project Goals
	•	Assist in the clinical classification of urine flow patterns
	•	Create high-quality labeled datasets for machine learning
	•	Enable intelligent uroflowmetry tools for home and clinical use

## 📜 License

This project is intended for non-commercial academic and research use only.  
For any other use, please contact the author.  
© 2025 Wei Zhou, TU Darmstadt – Institute of Adaptive Lighting Systems and Visual Processing

👤 Author

Wei Zhou
🌐 flow-labeling.de
📫 Feel free to open issues or contribute!

⸻
