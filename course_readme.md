# Communication Networks (7020511-1)

> **Ariel University**  
> Department of Computer Science | B.Sc. Program  
> **Textbook:** *Computer Networking: A Top-Down Approach* (9th Edition) – Jim Kurose & Keith Ross

---

## 📌 Course Overview

This repository contains course materials, notes, lab exercises, and assignments for **Communication Networks**. The course provides a modern, comprehensive introduction to the dynamic field of computer networking, covering foundational principles, architectural design, and practical insights required to understand modern networking infrastructures.

### Key Learning Outcomes
By the end of this course, you will be able to:
- Understand layered network architectures (specifically the **TCP/IP stack**) and core protocols including TCP, UDP, IP, DNS, and HTTP.
- Model, calculate, and analyze network performance metrics, including **packet delay**, **throughput**, and **routing efficiency**.
- Develop foundational practical skills in **IP addressing**, **routing configuration**, and **socket programming**.
- Understand both the **data plane** and **control plane** (traditional routing algorithms and modern Software-Defined Networking - SDN).

---

## 👥 Course Staff & Schedule

- **Lectures:** Sundays, 12:00 – 15:00
- **Lecturer:** Dr. Pinchas Weisberg ([pinhaswei@ariel.ac.il](mailto:pinhaswei@ariel.ac.il)) *(Office hours by appointment)*
- **Teaching Assistants:**
  - Anna Farber ([annaf@ariel.ac.il](mailto:annaf@ariel.ac.il))
  - Noam Asher ([noamasher55@gmail.com](mailto:noamasher55@gmail.com))

---

## 📚 Syllabus & Topic Roadmap

| Unit | Lessons | Core Topics | Highlights & Protocols |
|:---:|:---:|:---|:---|
| **1** | 1–2 | **Introduction & Core Concepts** | • What is the Internet & Protocols?<br>• Access Networks & Physical Media<br>• Packet Switching vs. Circuit Switching<br>• Layered Architecture (OSI & TCP/IP)<br>• Performance Metrics: Delay, Loss, and Throughput |
| **2** | 3–4 | **Application Layer** | • Web & HTTP (persistent/non-persistent, caching)<br>• Electronic Mail (SMTP, IMAP/POP3)<br>• Domain Name System (DNS)<br>• Video Streaming & Content Distribution Networks (CDNs) |
| **3** | 5–6 | **Transport Layer** | • Principles of Transport-Layer Services<br>• Connectionless Transport: UDP<br>• Principles of Reliable Data Transfer (rdt mechanisms)<br>• Connection-Oriented Transport: TCP (flow control, handshake)<br>• Principles of Congestion Control |
| **4** | 7–8 | **The Network Layer: Data Plane** | • Forwarding vs. Routing<br>• The Internet Protocol (IPv4, IPv6, Addressing, Subnetting)<br>• Generalized Forwarding & SDN (OpenFlow concepts) |
| **5** | 9–10 | **The Network Layer: Control Plane** | • Routing Algorithms (Link-State, Distance-Vector)<br>• SDN Control Plane<br>• Internet Control Message Protocol (ICMP) |
| **6** | 11 | **The Link Layer & LANs** | • Link Layer Services & Framing<br>• Multiple Access Protocols<br>• Switched Local Area Networks (LANs) |
| **7** | 12 | **Error-Detection & Correction** | • Parity Checks<br>• Internet Checksumming Methods<br>• Cyclic Redundancy Check (CRC) |

---

## 📊 Grading & Requirements

- **Final Exam:** 70% *(Passing grade required)*
- **Assignments & Defense:** 30% *(Includes assignment defense sessions)*
- **Attendance:** Active attendance bonus (as per course policy)

---

## 📁 Repository Structure

```text
.
├── lectures/             # Lecture summaries, slides, and notes
├── assignments/          # Homework assignments, lab work, and solutions
│   ├── hw1-application/  # Sockets, HTTP/DNS experiments
│   ├── hw2-transport/    # Reliable data transfer simulation / TCP analysis
│   └── hw3-network/      # Subnetting, routing algorithms, Wireshark captures
├── resources/            # Cheatsheets, reference RFCs, and extra reading
└── README.md
```

---

## 🛠 Recommended Tools & Setup

- **Wireshark:** Network packet analyzer for inspecting live traffic and protocol headers.
- **Python 3.x:** For socket programming exercises and protocol simulations.
- **Mininet / Cisco Packet Tracer:** Optional network emulation and topology testing.