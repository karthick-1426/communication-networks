NAME : KARTHICK E S
REG NO : 212223060114

# 🖧 Bus Topology Simulation Using Cisco Packet Tracer (ED-8)

## 📘 Computer Networks Laboratory Report

### Department of Computer Science & Engineering

---

# 📌 Experiment Details

| Field | Details |
|---|---|
| **Experiment No** | ED-8 |
| **Experiment Name** | Bus Topology Simulation |
| **Tool Used** | Cisco Packet Tracer |
| **Devices Used** | 3 Cisco 2960-24TT Switches + 6 PCs |
| **Topology** | Bus Topology |
| **Academic Year** | 2024 – 2025 |

---

# 🧠 Introduction

A network topology defines the arrangement of devices and communication paths in a computer network. It determines how nodes communicate and exchange data.

Bus topology is one of the earliest and simplest network architectures. In this topology, all devices share a single communication cable called the **backbone** or **bus**.

Data transmitted from one node travels through the entire bus and is received by every device connected to the network. Only the intended destination processes the packet.

Cisco Packet Tracer provides a virtual environment to simulate and analyze such network topologies without physical hardware.

---

# 🎯 Objectives

- Understand the concept of Bus Topology
- Design Bus Topology using Cisco Packet Tracer
- Simulate packet transmission between nodes
- Analyze advantages and disadvantages
- Compare with other topologies

---

# 🌐 Concept of Bus Topology

In Bus Topology:

- All devices connect to a single backbone cable
- Data travels in both directions
- Terminators are placed at both ends
- Only one device can transmit at a time
- CSMA/CD protocol controls communication

---

# 🔑 Key Characteristics

- Single shared communication medium
- Linear arrangement of devices
- Low installation cost
- Collision-prone network
- Easy to implement for small networks

---

# 🧩 Components Used

| Component | Purpose |
|---|---|
| Backbone Cable | Main transmission medium |
| Terminator | Prevents signal reflection |
| T-Connector | Connects devices to bus |
| NIC | Enables network communication |
| Cisco Switch | Connects multiple PCs |
| PCs | End-user nodes |

---

# 🖥️ Network Design

## Devices Used

| Device | Quantity |
|---|---|
| Cisco 2960-24TT Switch | 3 |
| PC-PT | 6 |
| Copper Straight Cable | 8 |

---

# 🌍 IP Addressing Scheme

| Device | IP Address |
|---|---|
| PC0 | 192.168.1.1 |
| PC1 | 192.168.1.2 |
| PC2 | 192.168.1.3 |
| PC3 | 192.168.1.4 |
| PC4 | 192.168.1.5 |
| PC5 | 192.168.1.6 |

Subnet Mask: `255.255.255.0`

Gateway: `192.168.1.254`

---

# 📊 Logical Diagram

```text
PC0          PC1          PC2
 |            |            |
[SW0]----[SW1 Central]----[SW2]
 |            |            |
PC3          PC4          PC5
```

---

# ⚙️ Cisco Packet Tracer Simulation Steps

1. Open Cisco Packet Tracer  
2. Add 3 Cisco 2960 switches  
3. Arrange them linearly  
4. Connect switches using copper cables  
5. Add 6 PCs  
6. Assign IP addresses  
7. Switch to Simulation Mode  
8. Create PDU packets  
9. Observe packet flow  

---

# 🖼️ Simulation Screenshot – PDU at Central Switch

<img width="1600" height="850" alt="CN 1" src="https://github.com/user-attachments/assets/54ee0e87-1c9c-44a4-a799-6dbdfc35dbc8" />


### 📌 Observation

The above screenshot shows the PDU packet reaching the central switch (**Switch1**).  
The packet is forwarded through the bus network to connected devices.

This demonstrates:

- Shared communication medium
- Packet forwarding mechanism
- Central switch communication flow

---

# 🖼️ Simulation Screenshot – PDU Propagation Across Network

<img width="1600" height="848" alt="CN 2" src="https://github.com/user-attachments/assets/41d73fab-a0c5-495a-9b4a-cea84bb70191" />


### 📌 Observation

The screenshot demonstrates packet propagation across multiple switches and PCs simultaneously.

This shows:

- Broadcast behavior in Bus Topology
- Packet transmission across all connected nodes
- Data propagation from source to destination

---

# 📡 Working Principle

## CSMA/CD Process

### 1. Carrier Sense
Device checks whether the bus is busy.

### 2. Multiple Access
All devices share the same medium.

### 3. Collision Detection
If two devices transmit simultaneously, collision occurs.

### 4. Back-off Algorithm
Devices wait random time before retransmission.

---

# 🔄 Data Transmission Example

## Example

- PC0 sends data to PC5  
- Packet moves through `Switch0 → Switch1 → Switch2`  
- PC5 accepts packet  
- Other PCs discard it  

---

# 🌟 Advantages of Bus Topology

- Low cost  
- Simple installation  
- Minimal cable requirement  
- Easy expansion  
- Suitable for small networks  

---

# ⚠️ Disadvantages of Bus Topology

- Single point of failure  
- Difficult troubleshooting  
- Performance decreases with traffic  
- Collision issues  
- Low security  

---

# 🏭 Real-World Applications

- CAN Bus in automobiles  
- Industrial automation  
- Early LAN networks  
- Educational labs  
- Embedded systems  

---

# 🔍 Comparison with Other Topologies

| Topology | Cost | Speed | Fault Tolerance |
|---|---|---|---|
| Bus | Low | Moderate | Poor |
| Star | Moderate | High | Good |
| Ring | Moderate | High | Moderate |
| Mesh | Very High | Very High | Excellent |
| Tree | High | High | Good |

---

# ✅ Conclusion

This experiment successfully demonstrated **Bus Topology using Cisco Packet Tracer**.

The simulation showed:

- Shared communication medium behavior  
- Packet broadcasting  
- CSMA/CD operation  
- PDU propagation  

Although Bus Topology is mostly replaced by **Star Topology** in modern networks, its concepts are still used in:

- CAN Bus  
- Embedded systems  
- Industrial communication  

This experiment provided practical understanding of shared-medium networking concepts.

---

# ❓ Viva / Question Bank

## Short Questions

1. Define Bus Topology  
2. What is CSMA/CD?  
3. What is a backbone cable?  
4. Why are terminators used?  
5. What happens during collision?  

---

## Long Questions

1. Explain Bus Topology with diagram  
2. Describe CSMA/CD in detail  
3. Explain simulation steps in Packet Tracer  
4. Compare Bus and Star Topology  

---

# 📚 End of Report

## ED-8 – Bus Topology Simulation Using Cisco Packet Tracer
