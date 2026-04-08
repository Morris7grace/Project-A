# Project-A
# 🤖 Chatbot System Design (BA Version)

## 📌 Overview
This project demonstrates a **Business Analyst perspective of system design** using a chatbot example.

The chatbot is designed to:
- Handle customer queries
- Reduce call center load
- Provide instant responses via WhatsApp/Web

---

## 🎯 Objective
Design a scalable chatbot system with:
- Clear architecture
- Defined components
- Data flow understanding
- Business assumptions and trade-offs

---

## 🏗️ High-Level Architecture



---

## 🔧 Components

### 1. API Gateway
- Entry point for all requests
- Handles authentication & routing

### 2. Chatbot Engine (NLP)
- Processes user input
- Identifies intent (e.g., "Check Policy", "Book Service")

### 3. Business Logic Layer
- Applies rules
- Calls APIs
- Validates data

### 4. Database
- Stores:
  - User data
  - Chat history
  - Transactions

### 5. External Services
- Payment gateway
- CRM system
- Insurance system APIs

---

## 🔄 Data Flow

1. User sends message via WhatsApp
2. API Gateway receives request
3. Chatbot engine processes intent
4. Business logic decides action
5. Data fetched from DB / External API
6. Response sent back to user

---

## 📊 Example Flow

User: "Check my policy status"

→ Intent detected: POLICY_STATUS  
→ Fetch policy from DB/API  
→ Return response: "Your policy is active"

---

## 📌 Assumptions

- Users are authenticated via mobile number
- APIs are available and reliable
- Chatbot supports English initially
- System handles up to 10,000 concurrent users

---

## ⚖️ Trade-offs

### Monolith Architecture
✅ Simple to build  
❌ Hard to scale  

### Microservices Architecture
✅ Scalable & flexible  
❌ Complex to manage  

👉 Decision:
Start with **Monolith**, later move to **Microservices**

---

## 🚀 Future Enhancements

- Multi-language support
- Voice-based chatbot
- AI-based recommendations
- Integration with mobile app

---

## 🧠 BA Perspective Covered

✔ Process understanding  
✔ Data flow clarity  
✔ System components  
✔ Business constraints  
✔ Decision-making (trade-offs)

---

## 📎 Tools You Can Use (Optional)

- Draw.io (for diagrams)
- Lucidchart
- Figma (for UI flow)

---

## 👨‍💼 Author
Created as part of Business Analyst / Product learning journey.
