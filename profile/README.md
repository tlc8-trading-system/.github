#  TLC 8 Trading System

Welcome to the **TLC 8 Trading System** — a distributed system working together to power a trading engine.

Our mission is to build a **scalable, and transparent trading platform** that:

- Accepts orders from external systems and clients  
- Validates those orders against strict internal and regulatory criteria  
- Identifies the best exchanges or venues for execution  
- Optimizes for best value and best execution guarantees  
- Provides real-time visibility to clients, admins, and operators  

This organization hosts all components that make up the TLC 8 trading ecosystem.

---

## 📁 Repositories

| Repo | Purpose | Main Tech |
|------|---------|-----------|
| [backend-api](https://github.com/Moonixp/bank-trading-application.git) | Core backend logic for end-to-end trading: order validation, routing, matching, execution, and integrations with liquidity providers/exchanges. | Spring Boot |
| [web-client](https://github.com/tlc8-trading-system/tlcg5-trading-system-web-client) | Web dashboard for clients, analysts, and operations teams to track orders, view trades, and monitor system health. | React, TypeScript, Vite |
| [mobile-client](https://github.com/tlc8-trading-system/trading-app-mobile-client) | React Native mobile app offering read-only insights, notifications, and account activity for users and admins. | React Native, Expo |

> Click any repo above to view its detailed README and code.

---

## 🧩 High-Level Architecture

The TLC 8 Trading System is designed around **service separation**, scalability, and reliability:

### **backend-api**
- Central trading coordinator  
- Validates incoming orders  
- Applies routing, pricing, and execution logic  
- Communicates with market data service
- Provides REST APIs to web and mobile clients  

### **service-web**
- Visualization layer for operational and client activities  
- Real-time views: orders, trades, execution paths  
- Admin tools for analytics, oversight, and system monitoring  

### **service-mobile**
- Lightweight mobile interface  
- Push notifications for order status and execution  
- Read-only access for enhanced security  

Together, these services enable the complete workflow from **order intake → validation → routing → execution → reporting**.

---

## 🚀 Getting Started

### 1. Clone the repositories

```bash
git clone https://github.com/Moonixp/bank-trading-application.git
git clone https://github.com/tlc8-trading-system/tlcg5-trading-system-web-client.git
git clone https://github.com/tlc8-trading-system/trading-app-mobile-client.git


### Run services locally
Backend (Spring Boot)



Web Client


Mobile App
```


📚 Documentation & Resources
Explore detailed design docs and requirements below:
 - Architectural Decision Records (ADRs) https://drive.google.com/drive/folders/12JuuNt_vtvSLvhSJKSnhhwHPDDLlXLBg?usp=sharing
 - API Exploration Notes https://docs.google.com/document/d/1eF8Zfz9pOm3_ky0nIdd8BjKScM26lxewcv-euQLxjTI/edit?usp=sharing
 - Core Requirements Document https://docs.google.com/document/d/1AWdFdl-naq1UpbtQbjoO9VFOshgYjmzTnjmEdzBiA80/edit?usp=sharing



🤝 Contributing
We welcome contributions from team members and collaborators.
 1 Pick an issue in the relevant repository.
 2 Create a feature branch: git checkout -b feature/<ticket-number>short-description  
 5 Ensure all tests pass before merging.
