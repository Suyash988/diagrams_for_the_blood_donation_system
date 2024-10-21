# Decentralized Blood Donation Management System with AI

This project aims to design and implement a decentralized blood donation management system using **private Ethereum blockchain** and **AI-powered predictive analytics** to address the limitations of traditional systems. 

The system ensures secure, transparent, and efficient management of blood donations, matching donors and recipients while leveraging blockchain for trust and AI for predictive analytics.

---

## 📋 **Project Overview**

The scope of the system includes the following:

### 1. **Blockchain-Enabled Data Management**
- Ensure **traceability**, **immutability**, **transparency**, and **auditability** by recording essential transactions (e.g., donation events, blood requests, and donor-recipient matching) on the blockchain.
- Store **non-critical and large data off-chain** using **IPFS** (InterPlanetary File System) to ensure scalability and maintain blockchain network efficiency.

### 2. **AI-Enhanced Prediction and Matching**
- Use **machine learning models** to predict future blood demand based on historical trends and medical emergencies.
- Implement **real-time donor-matching algorithms** based on blood type, location, and urgency.
- Utilize AI to analyze donor behavior patterns and provide **personalized reminders or rewards** to encourage regular donations.

### 3. **Decentralization and Security**
- Ensure the system is **decentralized** to eliminate the risk of single points of failure and enhance trust among stakeholders.
- Provide **data privacy** and **security** through blockchain encryption and secure off-chain storage.

---

## 📊 **Zero-Level Data Flow Diagram (DFD)**

Below is the **Zero-Level DFD** that illustrates the flow of information and interaction between the entities involved in the system. This diagram captures the major processes, data stores, and flows.

### **DFD Elements:**

1. **Entities:**
   - **Donor**: Provides blood donation information and details.
   - **Hospital**: Sends blood requests to the system.

2. **Process:**
   - **Blood Donation Management System**: 
     - Manages donation events, blood requests, and donor-recipient matching.
     - Interacts with both the blockchain and AI model.

3. **Data Stores:**
   - **Blockchain**: Stores donation events and blood request records for immutability and transparency.
   - **AI Model**: Provides predictive analytics and matching recommendations.

4. **Data Flows:**
   - **Donor Info & Donation Details**: Donor → System
   - **Blood Requests**: Hospital → System
   - **Donation Records**: System → Blockchain
   - **Predictive Analytics**: System → AI Model

---

## 📂 **DFD Diagram on draw.io**

To view or modify the **Zero-Level DFD**, you can import the following XML file into **draw.io**:

1. Open [draw.io](https://draw.io).
2. Select **File > Open from > Device**.
3. Import the `zero-level-dfd.xml` file provided in this repository.

---

## 🚀 **Technologies Used**

- **Private Ethereum Blockchain**: For secure, transparent, and immutable transactions.
- **IPFS**: For decentralized off-chain storage.
- **AI/ML Models**: For predictive analytics and donor behavior analysis.
- **Smart Contracts**: To automate donor-recipient matching.
- **draw.io**: For creating the Zero-Level DFD.

---

## 🛠 **How to Run**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Suyash988/diagrams_for_the_blood_donation_system.git
   cd blood-donation-system
