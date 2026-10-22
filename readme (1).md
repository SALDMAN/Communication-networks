# Communication Networks (7020511-1)

> **Ariel University**  
> School of Computer Science | B.Sc. Program  
> **Textbook:** *Computer Networking: A Top-Down Approach* (9th Edition) – Jim Kurose, Keith Ross  

---

## 📌 Course Overview

This repository contains lecture notes, assignments, code implementations, and review materials for **Communication Networks**. The course provides a modern, comprehensive introduction to computer networking principles, protocol design, network architectures, and practical hands-on insights into modern network infrastructure.

---

## 🎯 Learning Outcomes

By the end of the course, students will be able to:
- **Analyze Layered Architectures:** Understand the TCP/IP stack and key communication protocols (TCP, UDP, IP, DNS, HTTP).
- **Calculate Performance Metrics:** Evaluate packet delay (transmission, propagation, nodal processing, queuing), throughput, and routing efficiency.
- **Hands-on Networking:** Gain practical proficiency in IP addressing, subnetting, socket programming, and protocol analysis.
- **Data & Control Planes:** Understand traditional forwarding and routing algorithms alongside Software-Defined Networking (SDN) concepts.

---

## 👥 Course Staff & Schedule

- **Lectures:** Sundays, 12:00 – 15:00
- **Lecturer:** Dr. Pinchas Weisberg ([pinhaswei@ariel.ac.il](mailto:pinhaswei@ariel.ac.il)) *(Office hours by appointment)*
- **Teaching Assistants:**
  - Anna Farber ([annaf@ariel.ac.il](mailto:annaf@ariel.ac.il))
  - Noam Asher ([noamasher55@gmail.com](mailto:noamasher55@gmail.com))

---

## 🗺️ Syllabus & Topic Breakdown

| Unit | Lesson(s) | Topic | Key Concepts & Protocols |
| :--- | :--- | :--- | :--- |
| **Unit 1** | 1–2 | **Introduction & Architecture** | • What is the Internet? Protocols & Access Networks<br>• Layered Architecture (OSI vs. TCP/IP)<br>• Packet Switching vs. Circuit Switching<br>• Delay & Throughput Calculations |
| **Unit 2** | 3–4 | **Application Layer** | • Web & HTTP (Persistent/Non-persistent, Headers)<br>• Electronic Mail (SMTP, IMAP, POP3)<br>• DNS (Domain Name System architecture & resolution)<br>• Video Streaming & Content Distribution Networks (CDNs) |
| **Unit 3** | 5–6 | **Transport Layer** | • Multiplexing & Demultiplexing<br>• Connectionless Transport: UDP<br>• Principles of Reliable Data Transfer (rdt mechanisms)<br>• Connection-Oriented Transport: TCP (3-way handshake, flow control)<br>• Congestion Control Mechanisms |
| **Unit 4** | 7–8 | **Network Layer: Data Plane** | • Forwarding vs. Routing<br>• Internet Protocol (IPv4/IPv6 addressing, subnetting, NAT)<br>• Generalized Forwarding & SDN match-action abstractions |
| **Unit 5** | 9–10 | **Network Layer: Control Plane** | • Routing Algorithms (Link-State, Distance-Vector)<br>• Hierarchical Routing (OSPF, BGP)<br>• SDN Control Plane architectures<br>• ICMP (Internet Control Message Protocol, traceroute, ping) |
| **Unit 6** | 11 | **Link Layer & LANs** | • Link Layer services and framing<br>• Multiple Access Protocols (CSMA/CD, Aloha)<br>• MAC addressing, ARP, Ethernet, and Switches |
| **Unit 7** | 12 | **Error Detection & Correction** | • Parity checks & 2D Parity<br>• Internet Checksumming Methods<br>• Cyclic Redundancy Check (CRC) polynomial arithmetic |

---

## 📊 Grading & Requirements

- **Final Exam:** 70% *(Passing the exam is mandatory to pass the course)*
- **Assignments:** 30% *(Includes Assignment Defense)*
- **Bonus:** Attendance bonus

---

## 📂 Repository Structure

```text
├── lectures/       # Lecture summaries, slides, and notes
├── assignments/    # Homework submissions, code, and reports
├── labs/           # Socket programming, Wireshark packet analysis
└── README.md       # Course overview and syllabus roadmap
```

---

## 📖 Recommended Reference

- **Computer Networking: A Top-Down Approach**, 9th Edition  
  *Authors:* Jim Kurose, Keith Ross  
  *Publisher:* Pearson