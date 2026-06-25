#  Mobile Accessories Inventory Management System

An AI-powered inventory management solution built with **n8n**, **Airtable**, **Groq Llama 3.3**, and **AI Agents**. This system enables users to interact with inventory data using natural language, making product management faster and more efficient.

---

## Project Overview

Managing inventory manually can be time-consuming and prone to errors. This project automates inventory operations by integrating an AI agent with an Airtable database. Users can search products, retrieve inventory details, and update product information through simple conversational commands.

The AI Agent interprets user requests, accesses Airtable records, and performs the required actions automatically.

---

## Key Features

* Search inventory records using natural language
* AI-powered conversational assistant
* Airtable database integration
* Memory-enabled interactions
* Update product prices and costs
* Automated workflow using n8n
* Real-time inventory data retrieval

---

## Tech Stack

| Technology         | Purpose                        |
| ------------------ | ------------------------------ |
| n8n                | Workflow Automation            |
| Airtable           | Inventory Database             |
| Groq Llama 3.3 70B | Large Language Model           |
| AI Agent           | Decision Making & Tool Calling |
| Memory Buffer      | Context Retention              |

---

## Workflow

```text
User Message
      │
      ▼
AI Agent
      │
      ▼
Groq Llama 3.3 Model
      │
      ▼
Airtable Tools
 ├── Search Products
 └── Update Products
      │
      ▼
Response to User
```

---

##  Database Structure

The Airtable database stores information such as:

* SKU
* Product Name
* Category
* Subcategory
* Description
* Current Stock Quantity
* Reorder Threshold
* Unit Price
* Cost
* Supplier Information
* Product Location

---

## 🔍 Supported Operations

### Search Products

Users can search for:

* Product details
* Pricing information
* Stock information
* Product categories

Example:

```text
Find Samsung Fast Charger.
Show details of AirPods Pro.
Search for Type-C Charging Cable.
```

### Update Product Information

Users can update:

* Unit Price
* Product Cost

Example:

```text
Update Samsung Fast Charger price to 2500 PKR.

Change AirPods Pro cost to 1800 PKR.
```
## Benefits

* Reduces manual inventory management tasks
* Provides instant access to product information
* Improves inventory accuracy
* Saves time through automation
* Enables non-technical users to interact with database

## Future Enhancements

* Inventory stock updates
* Low stock alerts
* Supplier management
* Sales tracking
* Order management
* Analytics dashboard
* User authentication and authorization
* Voice-enabled inventory assistant

### n8n Workflow

*Add workflow screenshot here*

### Airtable Database

*Add Airtable screenshot here*

### AI Chat Interaction

*Add chatbot screenshot here*

---

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/Tanzeela-Atta/mobile-accessories-inventory-management.git
```

2. Import the workflow into n8n.

3. Create an Airtable base and table.

4. Configure:

   * Airtable API Token
   * Airtable Base ID
   * Groq API Key

5. Activate the workflow.

6. Start chatting with the AI inventory assistant.

## Author

**Tanzeela Atta**

Computer Engineering Student | AI Automation & Workflow Development Enthusiast

⭐ If you found this project useful, consider giving the repository a star.
