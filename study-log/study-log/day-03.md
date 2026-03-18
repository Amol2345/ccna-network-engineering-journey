# 📅 CCNA Study Log — Day 4 (12 March)

## 📚 Topics Covered
- TCP/IP Model (Deep Understanding)
- Encapsulation & Decapsulation
- Packet Flow Across Network
- ARP Process (Basic Understanding)
- Introduction to Routing Concepts

---

## 🧠 Key Concepts Learned

### 1. TCP/IP Model (5-Layer Model)
- Application
- Transport
- Network (Internet)
- Data Link
- Physical

📌 Important:
- Each layer has a specific role in communication.
- Data is processed layer by layer.

---

### 2. Encapsulation Process

Data flow:

Data → Segment → Packet → Frame → Bits

| Layer | PDU |
|------|-----|
Application | Data |
Transport | Segment |
Network | Packet |
Data Link | Frame |
Physical | Bits |

📌 Key Insight:
- Headers are added at each layer.

---

### 3. Decapsulation

Reverse process at receiver:

Bits → Frame → Packet → Segment → Data

📌 Happens at:
- Routers (partial)
- Destination host (complete)

---

### 4. Packet Flow Understanding

Basic flow:

PC → Switch → Router → Switch → Destination

📌 Important Rules:
- Switch uses **MAC address**
- Router uses **IP address**

---

### 5. ARP (Address Resolution Protocol)

Purpose:
- Convert IP → MAC

Process:
1. Broadcast request  
2. Device replies with MAC  
3. Entry stored in ARP table  

📌 Key Insight:
- Required before sending frame

---

### 6. Default Gateway Concept

- Used when destination is outside local network
- It is the router’s IP address

📌 Rule:
Same network → Direct communication  
Different network → Use default gateway  

---

## 🔍 Practical Understanding

- Observed packet flow using Packet Tracer
- Understood how devices communicate step-by-step
- Learned how encapsulation changes at each layer

---

## ⚠️ Difficult Areas

- TCP/IP flow initially confusing  
- Encapsulation vs Decapsulation  
- Understanding packet movement across devices  

---

## ✅ Completed Tasks

- ✔ Lecture completed  
- ✔ Lab completed  
- ✔ Flashcards (Day 1 & 2 already done)  





