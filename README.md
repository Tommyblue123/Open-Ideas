# Digital Marketplace for Open-Source Software

**URL:** [https://openideas.tech](https://openideas.tech)  
**Created by:** Tobi Adeoye | University of North Texas  

## 📌 Project Overview

The Digital Marketplace for Open-Source Software is a secure, user-friendly e-commerce platform tailored for developers, businesses, and open-source enthusiasts. It allows users to **buy**, **sell**, and **donate** open-source software in one centralized hub — bridging the gap between innovation and monetization.

Unlike traditional platforms such as GitHub, which lack integrated support for monetization, this marketplace empowers developers to earn from their contributions while continuing to embrace collaboration and transparency.

---

## 🌟 Key Features

### 🛍 Product Catalog
- Browse by category, brand, or filters
- Product listings with detailed descriptions, images, specs, and reviews
- Recommendations for related products

### 👤 User Management
- Secure registration and login (email, social logins)
- Profile updates, order history, and address book
- Password recovery and account security settings

### 🛒 Shopping Cart & Checkout
- Add/update/remove items with real-time pricing
- Secure checkout with support for PayPal, credit/debit cards
- Save carts, manage orders, and receive tracking updates

### 🔐 Security Features
- **Multi-Factor Authentication (MFA)** with miniOrange, Google Authenticator
- **End-to-End Encryption (E2EE)** using AES-256
- **PCI-DSS compliant payment gateways** (Stripe, PayPal)
- Security firewalls (Wordfence), vulnerability scanning (Wapiti, WPScan)
- SSL (HTTPS), CAPTCHA, and anti-phishing mechanisms

---

## 🧱 Architecture Overview

- **Frontend (Client-side):**  
  - Built with responsive WordPress themes for seamless desktop & mobile experiences
  - User interface for browsing, purchasing, and profile management

- **Backend (Server-side):**  
  - Deployed via Hostinger  
  - Handles business logic, user auth, database operations, and payment processing

- **Database Layer:**  
  - **Relational DB (PostgreSQL):** User data, product listings, and orders  
  - **NoSQL DB:** Session management, reviews, and real-time operations  

---

## 🔐 Security Audit Highlights

Security tools used:  
- **Wapiti**: Found no critical vulnerabilities; minor header config issues noted  
- **WPScan**: No plugin/theme vulnerabilities detected  
- **Wordfence**: Prevents brute-force and credential stuffing attacks

✅ Site uses HTTPS  
✅ All plugins/themes secure  
✅ MFA and CAPTCHA enforced  
✅ Payment data encrypted & tokenized  

---

## 🎯 Goals & Objectives

- Enable developers to earn from their open-source work
- Offer quality OSS with paid support and premium features
- Encourage collaboration and innovation in the OSS ecosystem
- Serve as a trusted OSS marketplace for individuals and businesses

---
