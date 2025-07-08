# AI-Powered-EV-Optimization

# 🔋 AI-Powered EV Optimization — n8n Workflow

This project contains an **n8n workflow** designed to optimize electric vehicle (EV) battery usage and provide real-time alerts and suggestions. It integrates with external APIs like **Twilio** and **location-based services** to deliver intelligent voice alerts and recommend nearby charging stations based on battery percentage and user location.

---

## 🚀 Features

- 📉 Tracks EV battery level input
- 📍 Accepts user location via form/webhook
- 📞 Sends **voice alerts** using **Twilio**
- 🗺️ Recommends **nearby EV charging stations**
- 🔄 Fully automated with no-code using **n8n workflow**

---

## 🛠 Technologies Used

- [n8n](https://n8n.io/) — workflow automation
- [Twilio](https://www.twilio.com/) — for sending voice messages
- Webhooks — to collect data from forms
- (Optional) Google Maps/OpenWeather API — for real-time recommendations

---

## 📂 Project Files

- `ev-battery-advisor-workflow.json`:  
  The exported n8n workflow you can import directly into your own n8n instance.

---

## 🧩 How to Use This Workflow

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Ruchikababu/AI-Powered-EV-Optimization.git
   cd AI-Powered-EV-Optimization
