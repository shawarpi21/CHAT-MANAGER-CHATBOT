# CHAT-MANAGER-CHATBOT
# Conversation Management & Classification
  
**Assignment:** Conversation Management & Classification using Groq API (Simulated)  
**Language:** Python (Google Colab Notebook)  
**Frameworks:** None (Standard Python only)

---

## **Project Overview**

This project demonstrates managing multi-turn conversations with an AI assistant, performing summarization, truncation, and structured information extraction using JSON schema.  

The implementation is **fully simulated**, so it works without requiring an actual Groq API key, while maintaining the same functionality as a real API integration.

---

## **Features Implemented**

1. **Interactive Chat Simulation**
   - Multi-turn conversation with greetings (“Hello/Hi Arpita Gupta”)  
   - Polite, professional, and realistic assistant responses  
   - Follow-up questions and confirmations  

2. **Conversation History Management**
   - Stores all user–assistant interactions  
   - Summarization after every k-th message  
   - Truncation options:
     - By number of conversation turns  
     - By character length  

3. **Structured JSON Extraction**
   - Extracts user details: `name`, `email`, `phone`, `location`, `age`  
   - Simulates OpenAI/Groq function calling for structured outputs  

4. **Persistence**
   - Save conversation history to JSON  
   - Load and display saved history  

5. **Professional Presentation**
   - Clear timestamps for each message  
   - Pretty-printed JSON outputs  
   - Markdown explanations in the notebook  

---

## **How to Run**

1. Open the provided **Google Colab notebook**.  
2. Run all cells sequentially.  
3. Interact with the simulated assistant via the sample chat demo.  
4. Observe:
   - Conversation history logging  
   - Summarization after every k-th message  
   - Truncation functionality  
   - JSON extraction of user details  

---

## **Project Structure**

