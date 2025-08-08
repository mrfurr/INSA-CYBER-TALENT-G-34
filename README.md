# 🇪🇹 PhishEye Ethiopia
*See the threat. Stop the scam.*

---

## 📌 Description
PhishEye Ethiopia is an open-source web security tool designed to **detect**, **log**, and **study** phishing attempts in an educational and ethical way.  
Built with **Flask, Python, MongoDB**, and security-focused practices, it gives Ethiopian cybersecurity learners a safe platform to understand how phishing works — without causing harm.

This project is part of the **INSA Summer Camp** initiative, developed to address Ethiopia’s growing phishing problem and raise awareness about online safety.

---

## 💡 Why the Name?
- **Phish** → From *phishing*, the cyberattack technique of tricking people into giving up sensitive information.  
- **Eye** → Symbolizing **vigilance** and **observation**, because to stop phishing, we must first *see it clearly*.  
Together: **PhishEye** means *“the watchful eye against phishing threats.”*

---

## 🛡️ Problem in Ethiopia
Ethiopia is experiencing rapid internet adoption — but with that growth comes risk:  
- Rising phishing attacks on social media, email, and banking platforms.  
- Low digital literacy in some communities makes people more vulnerable.  
- Few locally developed tools are available for training and awareness.  

PhishEye Ethiopia is our contribution to filling this gap.

---

## ⚙️ How It Works
1. **User Interaction** – A visitor clicks a suspicious link or button.  
2. **Data Logging** – PhishEye records:
   - IP address  
   - Browser user agent  
   - HTTP headers  
   - Timestamp of the visit  
3. **Storage** – Data is stored in MongoDB for later analysis.  
4. **Redirection** – The user is redirected to a safe page (e.g., Google).  

**Important:** This tool is meant for **training and research purposes only**. Misuse is strictly discouraged.

---

## 🚀 Features
✅ Logs detailed request information  
✅ MongoDB backend for analysis  
✅ Simple Flask web interface  
✅ Ready for integration into training environments  
✅ Focused on Ethiopia’s cyber landscape

---

## 🛠️ Tech Stack
- **Backend:** Python (Flask)  
- **Database:** MongoDB  
- **Frontend:** HTML  
- **Tools:** Kali Linux, Burp Suite (optional), Python requests, JSON

---

## 📂 Project Structure
```
PhishEye/
├── webapp.py
├── requirements.txt
├── templates/
│   └── index.html
└── README.md
```

---

## 🏃‍♂️ Quick Start
```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/PhishEye-Ethiopia.git
cd PhishEye-Ethiopia

# 2. Create a virtual environment
python3 -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run MongoDB (adjust connection if using cloud)
mongod --dbpath /path/to/your/db

# 5. Start the app
python webapp.py
```

---

## ❤️ Human Message
We all want Ethiopia’s internet to be a place of opportunity, not danger.  
PhishEye Ethiopia is here to **protect, educate, and empower** — so that people can browse without fear and our digital communities can grow strong.  
**Awareness is our best defense.**

---

## ⚠️ Disclaimer
This project is for **educational and research purposes only**.  
Do not use it to collect personal information without consent.  
The authors are not responsible for any misuse.
