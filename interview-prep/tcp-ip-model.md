# TCP/IP Model — Interview Preparation

## Question 1
What is the TCP/IP model?

### Answer
The TCP/IP model is a networking framework that describes how data travels across networks and the internet using a layered architecture.

The five layers of the model are:

1. Application
2. Transport
3. Network
4. Data Link
5. Physical

Each layer has specific responsibilities that enable reliable communication between devices.

---

## Question 2
What are the data units used at each TCP/IP layer?

### Answer

Application → Data  
Transport → Segment  
Network → Packet  
Data Link → Frame  
Physical → Bits

---

## Question 3
What is encapsulation?

### Answer
Encapsulation is the process of adding headers at each layer of the TCP/IP model as data moves from the application layer down to the physical layer.

Example flow:

Data → Segment → Packet → Frame → Bits

---

## Question 4
What is the difference between TCP and UDP?

### Answer

TCP:
- Reliable
- Connection-oriented
- Ensures ordered delivery

UDP:
- Faster
- Connectionless
- No delivery guarantee

---

## Question 5
Which devices operate at different TCP/IP layers?

### Answer

Switch → Data Link Layer  
Router → Network Layer  
Computer → All layers  
Cable → Physical Layer

---

## Question 6
When a router receives a packet, what address does it check?

### Answer
The router checks the **destination IP address** to determine the next hop and forward the packet to the correct network.

## Question 7
Explain TCP/IP model

### Answer

The TCP/IP model describes how data moves across networks using a layered architecture.
The application layer creates the data, the transport layer adds port numbers using TCP or UDP, the network layer adds IP addressing for routing, the data link layer adds MAC addressing for local delivery, and the physical layer transmits bits across the medium.
During transmission, data is encapsulated as it moves down the layers.
