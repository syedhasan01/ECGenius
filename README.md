# ECGenius 🫀💻

**ECGenius** is a real-time, IoT-based ECG monitoring and early heart disease detection system. It integrates ESP32 + AD8232 hardware, a Flask backend, and a Streamlit frontend to visualize ECG signals, vital stats, and AI-based diagnostic predictions.

---

## 🚀 Features

- 📡 Real-time ECG waveform streaming from ESP32 + AD8232
- ⚙️ Device connection status and alerts
- 📊 Streamlit dashboard with live vitals and charts
- 🧠 Machine Learning-based heart disease prediction
- 🤖 AI chatbot for ECG-related FAQs
- 📝 Export reports and health data to Excel
- 🌐 Optional cloud/server hosting for remote access

---

## 🛠️ Tech Stack

- **Hardware**: ESP32, AD8232 ECG Sensor  
- **Backend**: Python, Flask  
- **Frontend**: Streamlit  
- **ML Model**: Scikit-learn / TensorFlow  
- **Other Libraries**: Pandas, Matplotlib, Plotly, OpenCV, pyserial

---

## 📦 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/syedhasan01/ECGenius.git
cd ECGenius
2. Install Required Packages
bash
Copy
Edit
pip install -r requirements.txt

3. Connect Hardware
Connect ESP32 and AD8232 to your system

Set the correct COM port in your script

Flash ESP32 with Arduino sketch if needed

4. Start Flask Backend
bash
Copy
Edit
python backend.py
5. Run Streamlit Dashboard
bash
Copy
Edit
streamlit run app.py

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

👨‍💻 Author
Syed Mohammed Hasan Naqvi
📧 hasansyed2047@gmail.com
🔗 LinkedIn
💻 GitHub

🤝 Contributing
Pull requests are welcome. For significant changes, open an issue first to discuss what you'd like to change.

❤️ Acknowledgments
Biomedical IoT inspiration from real-world medical monitoring

ESP32 and AD8232 documentation and community examples

Python open-source ecosystem


