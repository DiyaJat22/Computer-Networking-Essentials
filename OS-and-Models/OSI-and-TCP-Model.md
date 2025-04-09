# 🌐 OSI Model vs TCP/IP Model – Networking Fundamentals

The OSI and TCP/IP models are conceptual frameworks used to understand and implement computer networking protocols. They define how data is transmitted from one device to another through different layers.

---

## 📦 OSI Model (Open Systems Interconnection)

The OSI model has **7 layers**, each with specific functions. It is a **theoretical model** used for understanding and designing a network system.

### 🧱 7 Layers of OSI Model:

| Layer No. | Layer Name       | Description                                                                 |
|-----------|------------------|-----------------------------------------------------------------------------|
| 7         | Application       | End-user interface; supports applications like browsers, email clients     |
| 6         | Presentation      | Data translation, encryption, and compression                              |
| 5         | Session           | Manages sessions and controls dialogues between devices                    |
| 4         | Transport         | Provides reliable or unreliable delivery; uses TCP or UDP                  |
| 3         | Network           | Handles logical addressing and routing (IP)                                |
| 2         | Data Link         | MAC addresses, error detection, and flow control                           |
| 1         | Physical          | Transmission of raw bit stream over physical medium                        |

---

## 🌐 TCP/IP Model (Transmission Control Protocol / Internet Protocol)

The TCP/IP model is a **practical model** used in real-world networking. It consists of **4 layers**, and it forms the basis of the modern internet.

### 🔹 4 Layers of TCP/IP Model:

| Layer No. | Layer Name       | Corresponding OSI Layers                     | Description                                       |
|-----------|------------------|---------------------------------------------|---------------------------------------------------|
| 4         | Application       | Application, Presentation, Session          | Provides network services to end-user applications|
| 3         | Transport         | Transport                                   | Ensures reliable data delivery (TCP/UDP)          |
| 2         | Internet          | Network                                     | Handles routing and addressing (IP)               |
| 1         | Network Access    | Data Link + Physical                        | Deals with physical transmission and MAC addressing|

---

## 🔁 OSI vs TCP/IP – Comparison Table

| Feature                   | OSI Model                              | TCP/IP Model                          |
|---------------------------|-----------------------------------------|----------------------------------------|
| Number of Layers          | 7                                       | 4                                      |
| Developed By              | ISO (International Standards Organization) | DARPA (U.S. Department of Defense)     |
| Approach                  | Theoretical and conceptual              | Practical and protocol-based           |
| Layer 3 Protocol          | IP                                      | IP                                     |
| Layer 4 Protocol          | TCP/UDP                                 | TCP/UDP                                |
| Common Usage              | Mostly used for learning and design     | Used in real-world networking          |
| Modularity                | More modular                            | Less modular                           |

---

## 🎯 Key Differences

- **OSI** separates **Presentation** and **Session** layers, while **TCP/IP** merges them into the **Application Layer**.
- **TCP/IP** is protocol-specific, whereas **OSI** is protocol-independent.
- **TCP/IP** is used in real-time data transmission over the Internet; **OSI** is used for teaching and architecture modeling.

---

## 📝 Summary Diagram

OSI Model TCP/IP Model

Application ─┐ Presentation ─┼──► Application Session ─┘

Transport ─┐ Transport Network ─┼──► Internet Data Link ─┐ Network Access Physical ─┘

---
