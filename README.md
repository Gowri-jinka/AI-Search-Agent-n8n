# AI Search Agent using n8n, Google Gemini & SerpAPI

## Project Overview

The AI Search Agent is a workflow automation project developed using n8n, Google Gemini, and SerpAPI. The system accepts user queries through a chat interface, processes them using Artificial Intelligence, retrieves relevant information from the web when required, and generates intelligent responses automatically.

This project demonstrates the integration of workflow automation, Large Language Models (LLMs), memory management, and web search capabilities to build an intelligent conversational assistant.

---

## Objectives

* Automate user query processing.
* Integrate AI capabilities using Google Gemini.
* Retrieve real-time information using SerpAPI.
* Maintain conversation context using memory.
* Demonstrate workflow automation using n8n.

---

## Technologies Used

* n8n Workflow Automation
* Google Gemini API
* SerpAPI
* AI Agent
* Simple Memory
* Chat Trigger

---

## Workflow Architecture

```text
User Query
      ↓
When Chat Message Received
      ↓
AI Agent
      ↓
Google Gemini Chat Model
      ↓
SerpAPI Search Tool
      ↓
Response Generation
```

---

## Workflow Components

### 1. When Chat Message Received

This node acts as the trigger for the workflow. Whenever a user enters a query, the workflow execution starts automatically.

### 2. AI Agent

The AI Agent serves as the central controller of the workflow. It receives user requests, coordinates communication between different nodes, and generates final responses.

### 3. Google Gemini Chat Model

Google Gemini is used as the Large Language Model (LLM) for natural language understanding and response generation.

Responsibilities:

* Understanding user intent
* Processing natural language queries
* Generating intelligent responses

### 4. Simple Memory

The Simple Memory node stores conversation context and enables the AI Agent to maintain continuity during interactions.

### 5. SerpAPI Search Tool

SerpAPI provides access to Google Search results and allows the workflow to retrieve real-time information from the web whenever necessary.

---

## Features

* AI-powered conversational assistant
* Real-time web search integration
* Workflow automation
* Context-aware interactions
* Intelligent response generation
* Easy-to-use chat interface

---

## Challenges Faced

### OpenAI API Quota Limitation

Initially, the workflow was configured using OpenAI APIs. During testing, API quota limitations prevented successful execution.

### Solution

The workflow was migrated to Google Gemini API, which successfully resolved the issue and enabled smooth execution.

### SerpAPI Authentication Error

Authentication issues occurred while configuring SerpAPI credentials.

### Solution

The issue was resolved by generating and configuring valid SerpAPI credentials.

---

## Project Outcome

The project successfully demonstrates how workflow automation and Artificial Intelligence can be combined to build an intelligent search assistant capable of:

* Understanding user queries
* Accessing external information sources
* Maintaining conversational context
* Generating accurate responses
* Automating the complete process

---

## Screenshots

### Workflow Design

<img width="1919" height="875" alt="Workflow Design" src="https://github.com/user-attachments/assets/ef3ff308-5fce-4694-8892-a2483317329c" />


### Workflow Execution and Generated Response

<img width="1916" height="929" alt="Workflow Execution and generated Response" src="https://github.com/user-attachments/assets/cf670fc4-592b-4f4a-bfaf-fed84d6c8d6d" />


---


## Future Enhancements

* Multi-language support
* Voice-based interaction
* Advanced memory management
* Integration with databases
* Integration with additional AI models

