# 📅 CCNA Study Log — Day 5 (14 March)

## 📚 Topics Covered
- Ethernet LAN Switching (Part 1)
- MAC Address Table
- Frame Forwarding
- Frame Flooding
- Frame Filtering

---

## 🧠 Concepts

### Ethernet LAN Switching

- Switch operates at Layer 2  
- Uses MAC address to forward frames  

---

### MAC Address Table

- Stores MAC addresses with corresponding ports  

Format:

MAC Address → Interface

- Learned dynamically  
- Built using source MAC of incoming frames  

---

### MAC Learning Process

1. Frame arrives at switch  
2. Switch reads source MAC  
3. Stores MAC with incoming port  

---

### Frame Forwarding

- If destination MAC is known → forward to specific port  

---

### Frame Flooding

- If destination MAC is unknown → send frame to all ports except incoming  

---

### Frame Filtering

- If destination MAC is known → only send to correct port  

---

### Broadcast Traffic

- Sent to all devices in network  

Example:

FF:FF:FF:FF:FF:FF  

---

## 🔍 Practice

- Observed MAC table behavior in Packet Tracer  
- Verified frame forwarding and flooding  
- Used `show mac address-table` command  

---
