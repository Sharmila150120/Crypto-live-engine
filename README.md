CryptoLive Engine – Real-Time Cryptocurrency Dashboard 
A full-stack web application that delivers real-time cryptocurrency market insights with a clean and responsive user interface. This project showcases asynchronous data handling, API integration, and dynamic UI updates without page reloads.

📌 Overview
CryptoLive Engine is designed to monitor cryptocurrency market trends by fetching live data from external APIs and presenting it in an interactive dashboard. It emphasizes performance, usability, and modern UI design principles.

✨ Features
📈 Live Price Tracking
Fetches real-time cryptocurrency data using the CoinGecko REST API.
🎨 Dynamic UI Updates
Automatically updates price changes with color indicators:
🟢 Green → Positive change
🔴 Red → Negative change
⚡ Zero-Reload Experience
Uses JavaScript fetch() and setInterval to refresh data every 30 seconds without reloading the page.
🌙 Modern Dark UI
Built with Tailwind CSS for a sleek, responsive, and fintech-inspired design.

🛠️ Tech Stack
Backend
Python 3.x
Flask
Frontend
HTML5
JavaScript (ES6+)
Tailwind CSS
Libraries & Tools
requests (Python)
CoinGecko API

📂 Project Structure

crypto-live-engine/
│── static/          
│── templates/       
│── app.py           
│── requirements.txt
│── README.md   

🚀 Installation & Setup
1️⃣ Clone the Repository
Bash
git clone https://github.com/YOUR_USERNAME/crypto-live-engine.git
cd crypto-live-engine
2️⃣ Create Virtual Environment (Optional but Recommended)
Bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
3️⃣ Install Dependencies
Bash
pip install -r requirements.txt
4️⃣ Run the Application
Bash
python app.py
5️⃣ Open in Browser

http://127.0.0.1:5000/
