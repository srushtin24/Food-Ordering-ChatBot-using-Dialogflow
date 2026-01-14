# Food Ordering ChatBot using Dialogflow

*This project is an AI-powered Food Ordering Chatbot designed to simulate a real-world food ordering and tracking experience.
The chatbot allows users to place food orders conversationally, modify orders dynamically, complete orders, and track order status — all through natural language interaction.*

*The system is built using Dialogflow ES for intent handling, FastAPI for backend webhook processing, and MySQL for persistent order storage.*

*This project demonstrates strong concepts in backend development, stateful conversations, API integration, and database-driven business logic.* <br><br>


🧩 ***Problem Statement*** <br>

Traditional food ordering systems rely on rigid user interfaces and manual navigation. <br>
This project explores how conversational AI can simplify the food ordering experience by allowing users 
to place, modify, and track orders using natural language, while maintaining conversational state 
and backend consistency.<br><br>


✨ ***Key Features*** <br>

🗣️ Natural language food ordering using Dialogflow<br>
➕ Add multiple food items with quantities<br>
➖ Remove items partially (e.g., remove 1 biryani from 2 biryani)<br>
🔄 Maintain session-based in-progress orders<br>
📦 Generate unique order IDs on order completion<br>
📍 Track order status using order ID<br>
🗄️ Persistent storage using MySQL & stored procedures<br>
🌐 Web-based chatbot UI using Dialogflow Messenger<br><br>

🛠️ ***Tech Stack*** <br>

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


🧠 ***System Architecture*** <br>

User interacts with the chatbot through a web interface powered by Dialogflow Messenger.  
Dialogflow processes user input using NLU and triggers a webhook request to the FastAPI backend.  
The backend handles business logic, manages conversational state, and interacts with a MySQL database 
for order persistence and tracking.<br><br>

User (Browser)<br>
↓<br>
Dialogflow Messenger<br>
↓<br>
Dialogflow ES (NLU, Intents, Contexts)<br>
↓<br>
FastAPI Webhook (Python)<br>
↓<br>
MySQL Database<br><br>

📸 ***Project Screenshots*** <br><br>


<p align="center">
   <img src="/images/1.png" width="800" hspace="40"><br><br>
   <img src="/images/2.png" width="800" hspace="40">
</p>

***New Order*** <br>

<p align="center">
   <img src="/images/3.png" width="800" hspace="40"><br><br><br>
   <img src="/images/4.png" width="800" hspace="40"><br><br><br>
   <img src="/images/5.png" width="800" hspace="40"><br><br><br>
   <img src="/images/6.png" width="800" hspace="40"><br><br><br>
   <img src="/images/7.png" width="800" hspace="40"><br><br><br>
   <img src="/images/8.png" width="800" hspace="40"><br><br><br>
</p>

***Order Tracking***<br>

<p align="center">
   <img src="/images/9.png" width="800" hspace="40">
</p>


