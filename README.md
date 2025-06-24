# Software Design Document: Draw It or Lose It (The Gaming Room)

## 📋 Project Summary

**Client:** The Gaming Room  
**Project:** Design a cross-platform operating environment to support the expansion of *Draw It or Lose It*, a multi-user drawing-based game currently limited to Android.

The Gaming Room is seeking to expand their game into a web-based, cross-platform environment that supports various client devices (e.g., desktops, tablets, smartphones). They partnered with Creative Technology Solutions (CTS) to architect the system infrastructure and environment before beginning software development. This project involved analyzing operating platforms, memory and storage needs, network distribution, and security considerations to ensure a scalable, reliable, and secure client-server architecture.

---

## ✅ What Went Well

I was particularly effective at:
- Translating software requirements into platform-specific constraints.
- Applying patterns like Singleton and Iterator within the object model to meet design constraints.
- Evaluating multiple OS platforms across development, server, and client contexts.
- Addressing scalability, storage, and memory management for media-heavy gameplay.
- Clearly separating the domain model from architectural decisions, which helped create a modular and extensible design.

---

## 💡 Design Process Reflection

Working through this Software Design Document (SDD) helped reinforce how essential it is to build a strong technical foundation **before** writing a single line of code. By evaluating operating system platforms, memory and storage needs, and system architecture first, I was able to design a scalable environment that supports both development and production needs.

One of the most helpful aspects was documenting environment requirements. This gave structure to decisions about deployment pipelines, toolchains, and compatibility between development and runtime environments.

---

## 🔧 What I Would Improve

If I were to revise one part of the SDD, I would enhance the **System Architecture View** with more visual diagrams and flowcharts. Visualizing server-client communication, image rendering workflows, and authentication processes would improve clarity for both technical and non-technical stakeholders.

---

## 👥 Understanding and Meeting User Needs

The client required a scalable environment capable of supporting real-time, multi-user gameplay. I interpreted these needs by:
- Using platform evaluation matrices to select a cost-effective and scalable server OS (Linux).
- Ensuring security and authentication (OAuth) across distributed systems.
- Designing the system with horizontal scaling in mind to handle fluctuating user loads.

It’s vital to align architecture with user needs because performance, usability, and reliability all stem from technical decisions made early in the planning phase.

---

## 🛠️ Future Design Strategies

For similar projects, I would continue to:
- Start with environment evaluation before tool selection.
- Use platform compatibility tables to inform design trade-offs.
- Include diagrams for architecture and component interactions.
- Employ design patterns (like Singleton and Iterator) where they naturally align with business logic.

Designing software isn't just about code. It's about setting up the right ecosystem where that code can thrive.

---

## 🧠 Technologies & Topics Covered

- Operating System Architecture (Linux, macOS, Windows)
- Distributed Systems and Networking
- Memory and Storage Management
- Security Considerations (OAuth, multi-platform protection)
- Object-Oriented Design (Singleton, Inheritance, Iterator Pattern)

---

## 📁 Repository Structure

/OperatingPlatforms
│
├── CS 230 Project Software Design.docx # Final design document
├── README.md # This file
