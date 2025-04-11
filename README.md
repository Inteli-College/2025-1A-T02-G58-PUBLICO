# 2025-1A-T02-G58-PUBLIC

# 📄 PUBLIC REPORT – Module 1

## 1. PROJECT INFORMATION

**Project Title:** Intelligent Recommendation Platform for Truck Parts  
**Team:** Julia Rodrigues Togni  
**Module:** Development – Sprint 1  
**Submission Date:** 04/11/2025

---

## 2. MODULE OBJECTIVE

To develop the initial structure of a digital platform focused on recommending truck parts, based on user input in natural language interpreted by an AI model (DeepSeek). Activities included market research, interviews with industry professionals, definition of functional and non-functional requirements, proposal of system architecture, AI behavior diagram, business model structuring, and planning for upcoming stages.

---

## 3. MARKET RESEARCH

### 3.1 COMPETITOR ANALYSIS

- **Mercado Livre:** generalist platform with a high volume of listings but limited tools to validate technical compatibility of parts.
- **Tracbel:** parts distributor with a digital operation; 50% of its sales occur through e-commerce.
- **Mundo do Caminhão:** specialized catalog, but no use of AI or natural language-based recommendations.

### 3.2 MARKET GAPS IDENTIFIED

The truck parts sector shows structural challenges:

- **Dependence on imports** and logistical difficulties post-pandemic;
- **Strikes and service disruptions** that affect cargo clearance times;
- **Shortage of inputs** like packaging and cardboard that impact distribution;
- **Lack of smart recommendation platforms** based on problem descriptions;
- **Limited digital support for truck drivers’ purchasing journey.**

---

## 4. USER RESEARCH

### 4.1 INTERVIEWED PROFILES

- **Independent truck driver:** responsible for their own vehicle’s maintenance; reported difficulties in finding compatible parts and mainly uses Mercado Livre.
- **Truck parts sales representative:** works in customer and post-sale support; highlighted communication issues and order errors due to incomplete customer information.

### 4.2 IDENTIFIED CHALLENGES

- Lack of standardization in how users describe issues;
- Difficulty accessing real-time pricing and stock data;
- Time spent verifying part compatibility;
- Increasing demand for faster and more accurate service.

### 4.3 PERCEIVED BENEFITS

- Faster part selection process;
- Reduction in ordering errors;
- Greater autonomy for users to resolve basic doubts;
- Less demand on sales team resources.

---

## 5. REQUIREMENTS MAPPING

### 5.1 FUNCTIONAL REQUIREMENTS

| Requirement                   | Description                                                              |
|-------------------------------|--------------------------------------------------------------------------|
| Natural language search       | Allow users to describe their needs in plain language.                   |
| Parts recommendation          | Suggest compatible parts based on input.                                 |
| Search history                | Store users' past searches for reference.                                |

### 5.2 NON-FUNCTIONAL REQUIREMENTS (AI)

| Requirement                   | Description                                                              |
|-------------------------------|--------------------------------------------------------------------------|
| Accuracy                      | Achieve at least 90% correctness in part recommendations.                |
| Response time                 | Return results within 2 seconds for 95% of queries.                      |
| Contextual interpretation     | Understand model and year described by the user.                         |
| Explainability                | Provide reasoning for recommendations when possible.                     |

---

## 6. SYSTEM ARCHITECTURE

| Layer             | Suggested Technology                             |
|-------------------|--------------------------------------------------|
| Frontend          | React.js                                         |
| Backend           | Node.js                                          |
| AI                | DeepSeek API (language model)                    |
| Database          | PostgreSQL + Elasticsearch                       |

A visual diagram showing relationships between layers and data flow was included in the module.

---

## 7. SUCCESS CRITERIA

| Indicator                  | Target Value                                                                  |
|----------------------------|-------------------------------------------------------------------------------|
| Recommendation accuracy    | ≥ 90% correct suggestions for parts.                                          |
| User satisfaction          | Average ≥ 4 out of 5 in satisfaction ratings.                                 |
| System response time       | 95% of system responses within 2 seconds.                                     |
| Integrated suppliers       | At least 50 supplier partners within the first year.                          |
| Monthly user engagement    | Reach 10,000 monthly searches by the sixth month.                             |

---

## 8. NEXT STEPS

- Begin prototyping the interface with natural language input simulation;  
- Validate the recommendation flow with real-world data;  
- Build an initial supplier integration base;  
- Prepare for testing phase with end users.  
