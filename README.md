# 🚀 Learn Model Context Protocol (MCP) from Scratch

This project is a hands-on guide to understanding and building with the **Model Context Protocol (MCP)** — a new open standard that allows **Large Language Models (LLMs)** to securely and dynamically connect to **real-time data, tools, and APIs**.

---

## ✨ Features

- 🧠 **What MCP is** and **why it matters** for LLMs  
- 🔗 **How MCP connects AI models to live data sources**  
- ⚙️ **How to build your first MCP server** in **Node.js** using the official SDK  
- 🧩 **Practical examples** of integrating MCP with custom tools or APIs

---

## 🏗️ Project Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/MCP-Currency-Converter.git
cd MCP-Currency-Converter
```
### 2️⃣ Install dependencies
```bash
 npm install
```
This project uses:
```bash
"@modelcontextprotocol/sdk": "^1.19.1",
"zod": "^3.25.76"
```
### 3️⃣ Run the MCP Server
```bash
node currencyConverted.js
```
Your MCP server will start locally and connect your AI agent to real-time currency data.

## 🧠 About Model Context Protocol

**MCP (Model Context Protocol)** is an open standard by Anthropic that enables LLMs to:

- Access real-time, contextual data safely  
- Use tools and external APIs directly  
- Maintain up-to-date and relevant responses  

It’s designed to make AI systems **more interactive, reliable, and extensible** — ideal for custom AI agents and GenAI applications.

---

## 🪄 Example Use Case

This project demonstrates how to build a **Currency Converter MCP Server** that:

- Fetches **live currency exchange rates**  
- Responds to requests from AI models or local MCP clients  
- Can be extended to other financial data or APIs

---

## 🧩 Tech Stack

- **Node.js** — Server runtime  
- **@modelcontextprotocol/sdk** — MCP SDK for Node  
- **Zod** — Schema validation for structured data

