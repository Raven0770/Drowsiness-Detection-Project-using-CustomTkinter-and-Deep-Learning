# 🚗 Driver Drowsiness Detection & Monitoring System

An intelligent **real-time drowsiness detection desktop application** built with Python that uses computer vision and deep learning to monitor driver alertness, trigger warnings, and generate analytics reports — all inside a modern desktop UI.

This project combines **AI detection + live monitoring + analytics dashboards** to create a complete safety monitoring solution.

---

## 📸 Overview

The system uses a webcam to detect:

* 😴 Drowsy eye states
* 🥱 Yawning
* ⚠️ Prolonged inactivity / fatigue indicators

When unsafe behavior is detected, the app:

* Plays alert sounds
* Logs incidents automatically
* Stores analytics data
* Generates reports
* Can optionally send WhatsApp alerts

---

## ✨ Key Features

### 🎥 Real-Time Detection

* Live webcam monitoring
* YOLO-based deep learning model
* Fast, lightweight inference

### 🔔 Smart Alert System

* Audio warnings for unsafe states
* Visual flash alerts
* Break timer reminders

### 📊 Analytics Dashboard

* Incident tracking
* Event trends
* Alert frequency analysis
* Historical monitoring

### 🧾 Logging & Reports

* Automatic log generation
* Raw log viewer
* Report section inside the GUI

### 💬 Notification Integration

* WhatsApp alert support (via PyWhatKit)

### 🖥️ Modern Desktop UI

* Built with **CustomTkinter**
* Clean multi-frame interface
* Easy navigation

---

## 🧠 How It Works

1. Webcam feed is captured in real time.
2. Frames are processed through a trained detection model.
3. Drowsiness/yawning events are detected.
4. Alerts are triggered if thresholds are exceeded.
5. Events are stored in logs.
6. Analytics dashboards visualize driver behavior.

---

## 🧱 Project Structure

```
CustomKTinker/
│
├── app_launcher.py            # Main application entry
├── config.py                  # Configuration settings
├── user_settings.json         # User preferences
│
├── frames/                    # GUI modules
│   ├── analytics_frame.py
│   ├── rawlogs_frame.py
│   └── reports_frame.py
│
├── live_app/                  # Real-time detection engine
│   ├── app_core.py
│   ├── detector.py
│   ├── logger.py
│   ├── break_timer.py
│   ├── ui.py
│   └── run.py
│
├── model/
│   └── final_model.pt         # Trained model
│
└── requirements.txt
```

---

## 🧰 Tech Stack

* **Python**
* **OpenCV**
* **Ultralytics YOLO**
* **CustomTkinter**
* **Tkinter**
* **Pillow (PIL)**
* **Pygame**
* **PyWhatKit**

---

## 🚀 Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/CustomKTinker.git
cd CustomKTinker
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / Mac**

```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
python app_launcher.py
```

---

## ⚙️ Configuration

Edit:

```
config.py
user_settings.json
```

You can customize:

* Detection sensitivity
* Alert behavior
* Notification settings
* UI appearance
* Model path

---

## 📊 Analytics & Reporting

The app includes:

* Real-time incident tracking
* Historical analysis
* Behavior summaries
* Log inspection tools

Useful for:

* Driver safety monitoring
* Research projects
* AI demo applications
* Computer vision showcases

---

## 🧪 Model

The detection model is stored as:

```
model/final_model.pt
```

You may replace it with your own trained YOLO model if label formats match.

---

## 🛣️ Roadmap (Future Improvements)

* Cloud syncing for logs
* Multi-user support
* Mobile notifications
* Driver fatigue scoring
* Auto-generated PDF reports
* Multi-camera support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repository
2. Create a new branch
3. Commit your changes
4. Open a pull request

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

THANU PRASAD. D
 - GitHub: [@Raven0770](https://github.com/Raven0770)

S. SUVEETHA
 - GitHub: [@suvii-15](https://github.com/suvii-15)

S. PRIYA DARSHINI
 - GitHub: [@](https://github.com/)

SRUSHTI LAKKAPLA
 - GitHub: [@](https://github.com/)

---
