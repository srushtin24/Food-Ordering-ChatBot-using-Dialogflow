# Food Ordering ChatBot using Dialogflow

***This project is an AI-powered Food Ordering Chatbot designed to simulate a real-world food ordering and tracking experience.
The chatbot allows users to place food orders conversationally, modify orders dynamically, complete orders, and track order status — all through natural language interaction.***

***The system is built using Dialogflow ES for intent handling, FastAPI for backend webhook processing, and MySQL for persistent order storage.***

***This project demonstrates strong concepts in backend development, stateful conversations, API integration, and database-driven business logic.***<br><br>

### ✨ Key Features<br>

🗣️ Natural language food ordering using Dialogflow<br>
➕ Add multiple food items with quantities<br>
➖ Remove items partially (e.g., remove 1 biryani from 2 biryani)<br>
🔄 Maintain session-based in-progress orders<br>
📦 Generate unique order IDs on order completion<br>
📍 Track order status using order ID<br>
🗄️ Persistent storage using MySQL & stored procedures<br>
🌐 Web-based chatbot UI using Dialogflow Messenger<br><br>

### 🛠️ Tech Stack<br><br>

1. Frontend
- HTML
- CSS
- Dialogflow Messenger<br><br>

2. Backend
- Python
- FastAPI (Webhook Server)<br><br>

3. AI / NLP
- Dialogflow ES (Intents, Entities, Contexts)<br><br>

4. Database
- MySQL<br><br>


### 📸 Project Screenshots


<p align="center">
   <img src="/images/1.png" width="200" hspace="40">  
   <img src="/images/2.png" width="200" hspace="40">
</p>

Add items


Remove items



Order completion



Order tracking









🚀 ***How to Run Locally***

1️⃣ Clone the Repository
```
git clone https://github.com/yourusername/Bangalore-Home-Price-Predictor.git
cd Bangalore-Home-Price-Predictor
```
2️⃣ Install Dependencies
```
pip install -r requirements.txt
```
3️⃣ Run the Flask Server
Navigate to the server folder and run:
```
python server.py
```
4️⃣ Open the Frontend
Navigate to the client folder and open:
```
app.html
```
