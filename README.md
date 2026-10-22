# Communication Networks (7020511-1)

> **Ariel University**  
> School of Computer Science | B.Sc. Program  
> **Textbook:** *Computer Networking: A Top-Down Approach* (9th Edition) – Jim Kurose, Keith Ross  

---

## 📌 Course Overview

This repository contains notes, exercises, code implementations, and reference materials for the **Communication Networks** course. The course provides a modern, comprehensive introduction to the principles and architectures of computer networking, covering everything from core theoretical models to real-world protocol implementations.

---

## 🎯 Learning Outcomes

By the end of the course, students will be able to:

* **Layered Architectures:** Understand layered network models (notably the TCP/IP and OSI stacks) and key protocols across layers (HTTP, DNS, TCP, UDP, IP, ICMP).
* **Performance Analysis:** Calculate, model, and analyze network performance metrics, including throughput, packet delay components ($d_{\text{proc}}$, $d_{\text{queue}}$, $d_{\text{trans}}$, $d_{\text{prop}}$), and loss rates.
* **Practical & Implementation Skills:** Gain foundational skills in socket programming, IP addressing, subnetting, and network troubleshooting tools.
* **Control & Data Planes:** Differentiate between traditional forwarding/routing algorithms and modern Software-Defined Networking (SDN) paradigms.

---

## 👥 Course Staff & Schedule

* **Lecture Hours:** Sundays, 12:00 – 15:00
* **Method of Instruction:** Frontal lectures
* **Lecturer:** Dr. Pinchas Weisberg ([pinhaswei@ariel.ac.il](mailto:pinhaswei@ariel.ac.il)) *(Office hours by appointment)*
* **Teaching Assistants:**
  * Anna Farber ([annaf@ariel.ac.il](mailto:annaf@ariel.ac.il))
  * Noam Asher ([noamasher55@gmail.com](mailto:noamasher55@gmail.com))

---

## 🗺️ Detailed Syllabus & Course Plan

| Unit | Lessons | Topic Area | Detailed Topics & Protocols |
| :---: | :---: | :--- | :--- |
| **1** | 1–2 | **Introduction & Overview** | What is the Internet? Definition of protocols; Network edge & access networks; Layered architecture; Packet switching vs. circuit switching; Delay, loss, and throughput in packet-switched networks. |
| **2** | 3–4 | **Application Layer** | Principles of network applications; The Web and HTTP; Electronic Mail (SMTP, IMAP, POP3); DNS (Domain Name System); Video streaming and Content Distribution Networks (CDNs). |
| **3** | 5–6 | **Transport Layer** | Transport-layer services; Multiplexing and demultiplexing; Connectionless transport (UDP); Principles of Reliable Data Transfer (rdt protocols); Connection-oriented transport (TCP segment structure, flow control, connection management); Principles of congestion control and TCP Congestion Control. |
| **4** | 7–8 | **The Network Layer: Data Plane** | Overview of network layer; Forwarding vs. routing; Router architecture; The Internet Protocol (IPv4, addressing, CIDR, DHCP, NAT, IPv6); Generalized forwarding and SDN data plane. |
| **5** | 9–10 | **The Network Layer: Control Plane** | Routing algorithms (Link-State / Dijkstra, Distance-Vector / Bellman-Ford); Intra-AS routing (OSPF); Inter-AS routing (BGP); The SDN control plane; Network management and ICMP. |
| **6** | 11 | **The Link Layer & LANs** | Services provided by the link layer; Error detection and correction techniques; Multiple access links and protocols (MAC); Switched local area networks (Ethernet, switches, VLANs). |
| **7** | 12 | **Error Detection & Correction** | Parity checks; Checksumming methods; Cyclic Redundancy Check (CRC). |

---

## 📊 Grading Policy

* **Final Exam:** 70% *(Required passing grade on exam)*
* **Assignments & Homework:** 30% *(Includes Assignment Defense)*
* **Attendance:** Bonus

---

## 📂 Repository Structure

```plaintext
.
├── lectures/           # Lecture slides, notes, and summary sheets
├── assignments/        # Homework assignments, problem sets, and code
├── labs/               # Socket programming scripts, Wireshark packet captures
└── README.md           # Course overview and syllabus reference
```

---

## 📖 Recommended Literature

* **Main Textbook:** *Computer Networking: A Top-Down Approach*, 9th Edition, Jim Kurose & Keith Ross.
* **Exam Material:** All theoretical concepts, mathematical models, and practical implementations presented throughout the course.