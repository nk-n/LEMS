# Lab Equipment Management System — Project Hub

A full-stack web-based equipment management system for laboratory developed as part of the course **01418471: Software Design and Development** at Kasetsart University.
This hub consolidates all related repositories, documentation, and system architecture.

---


## 🏗 System Overview
The system is composed of two primary components working together to deliver a complete equipment management workflow.

---

### **1. Frontend Web Application (Next.js + Tailwind CSS)**  
A responsive, modern interface for students, staff, and administrators.

#### **Features**
- Browse, borrow, and return equipment  
- Receive notifications when items become available  
- Submit repair/requisition request forms  
- Add and edit equipment information  
- Manage users, roles, and permissions  
- View system logs and activity history  

**Repository:**  
👉 [github.com/nk-n/lems-frontend](https://github.com/nk-n/lems-frontend)

---

### **2. Backend Services (Go + Echo Framework + Docker)**  
Implements all business logic, data operations, and integrations.

#### **Capabilities**
- Borrow/Return workflow processing  
- Equipment inventory management  
- User and role administration  
- Borrow queue management with priority logic  
- Repair/requisition request form handling  
- System logging and audit trail  
- Real-time notifications via WebSockets  

**Repository:**  
👉 [github.com/nk-n/lems-backend](https://github.com/nk-n/lems-backend)

---

## 🔧 Architecture Diagram (Simplified)
             ┌──────────────────────────────┐
             │         Web Frontend         │
             │     (Next.js + Tailwind)     │
             └───────────────▲──────────────┘
                             │ HTTPS (REST)
                             │ WebSockets
             ┌───────────────┴───────────────┐
             │         Backend API           │
             │     (Go + Echo + Docker)      │
             └───────────────▲───────────────┘
                             │
                       Database Layer
                    (PostgreSQL + MinIO)
---

## 📡 Technologies
### **Frontend**
- Next.js  
- Tailwind CSS  
- TypeScript  

### **Backend**
- Go  
- Echo framework  
- Docker  
- WebSockets  

### **Other**
- JWT-based authentication
- RBAC (Role-Based Access Control)  
- PostgreSQL  
- MinIO (object storage)

---


## 👨‍🔬 Authors
- Thanakrit Trakanjan
- Pongsiri Gittiyoottanawin
- Rugsit Rungrattanachai
- Narakorn Thanapornpakdee
- Pannathorn Suetrong


