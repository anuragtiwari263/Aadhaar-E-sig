# 🔏 Aadhaar E-Sign System

A secure and scalable Aadhaar-based e-signature system that facilitates digital document signing using UIDAI services. The project includes modules for user onboarding, wallet management, notifications, and audit logging of e-sign workflows.

---

## 📌 Project Overview

The Aadhaar E-Sign project enables users to digitally sign documents using their Aadhaar number and OTP-based verification. It streamlines government-compliant workflows with full traceability and real-time communication.

---

## 🧩 Modules Covered

### 👤 User Onboarding
- Registration and identity verification
- KYC checks and Aadhaar number linking
- OTP generation and validation via UIDAI APIs

### 💰 Wallet Module
- Wallet creation and linking with user accounts
- Balance check, wallet credit/debit logs
- Used for deducting charges for each successful e-sign request

### ✉️ Notification Module
- Email and SMS integration via third-party services
- Event-based triggers: onboarding, OTP delivery, success/failure alerts
- Verified message templates for audit compliance

### 📄 E-Sign Workflow
- API to initiate document signing using Aadhaar
- Document upload, consent request, OTP validation
- Real-time status tracking

### 🕒 History & Audit Trail
- Logs each transaction: signer details, document ID, timestamp, status
- Maintains integrity and traceability for compliance and audits

---

## 🧪 Testing Performed

### ✅ Manual Testing
- Functional testing of all modules (UI and backend)
- End-to-end user flow validation
- Form validation & field-level input testing

### 🔄 Regression Testing
- Ensured stability of key features after updates
- Re-ran test cases for core onboarding and e-sign flows

### 🛠 API Testing (Postman)
- Verified endpoints for:
  - Aadhaar authentication
  - E-sign document initiation
  - OTP generation and verification
  - Wallet balance and transaction logs

### 🚦 Performance Testing (JMeter)
- Load testing of e-sign API under concurrent users
- Wallet module stress-tested under peak loads

---

## 📂 Folder Structure (if applicable)
