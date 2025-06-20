# Chatbot_for_food_app
# 🤖 Chatbot for Food Delivery

A smart, full-stack chatbot system for food ordering and delivery. Combines a Dialogflow-powered conversational assistant, a FastAPI backend, and a MySQL database with a user-friendly web interface.

---

## 📌 Features

- 💬 **Dialogflow Chatbot** for natural conversation with customers  
- ⚙️ **FastAPI Backend** for handling requests and database interaction  
- 🛢️ **MySQL Database Integration** (importable dump included)  
- 🌐 **Responsive Frontend** for placing orders and interacting with the bot  
- 🔐 **HTTPS Support** via **ngrok tunneling**  

---

## 🧱 Tech Stack

| Component         | Technology            |
|------------------|-----------------------|
| Chatbot           | Dialogflow            |
| Backend           | FastAPI (Python)      |
| Database          | MySQL                 |
| Frontend          | HTML, CSS, JavaScript |
| HTTPS Tunneling   | ngrok                 |

---

## 📂 Directory Structure

chatbot_for_food_delivery/
├── backend/ # FastAPI backend app
├── db/ # MySQL database dump (to import via Workbench)
├── dialogflow_assets/ # Dialogflow intents, entities, config
└── frontend/ # Web interface files


---

## 🚀 Getting Started

### 🔧 Install Dependencies

#### Option A: Manually install
```bash
pip install mysql-connector-python
pip install "fastapi[all]"
