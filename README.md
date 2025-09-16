# CHAT-MANAGER-CHATBOT
# Conversation Management & Classification

**Author:** Arpita Gupta  
**Assignment:** Conversation Management & Classification using Groq API (Simulated)  
**Language:** Python (Google Colab Notebook)  
**Frameworks:** None (Standard Python + Simulated API Calls)  

---

## Project Overview

This project demonstrates managing multi-turn conversations between a user and an AI assistant, performing summarization, truncation, and structured JSON-based information extraction.  

It is implemented as a **fully simulated solution** to match assignment requirements, running smoothly without an actual Groq API key, while providing realistic functionality.

---

## Features Implemented

1. ✅ **Interactive Chat Simulation**  
   - User starts with greetings ("Hello" / "Hi")  
   - Polite, professional responses from the assistant  
   - Multi-turn interaction with follow-up questions and confirmations  

2. ✅ **Conversation History Management**  
   - Stores user and assistant messages sequentially  
   - Periodic summarization after every k-th message  
   - Options to truncate by:
     - Number of conversation turns  
     - Character/word limit  

3. ✅ **Structured JSON Extraction**  
   - Extracts key user details:  
     - `name`  
     - `email`  
     - `phone`  
     - `location`  
     - `age`  
   - Simulated structured extraction function mimicking Groq/OpenAI function call  

4. ✅ **Persistence**  
   - Save conversation history as `conversation_log.json`  
   - Reload and display saved conversation history  

5. ✅ **Professional Formatting**  
   - Clear timestamps for each message  
   - Pretty-printed JSON extraction results  
   - Well-documented and clean code  

---

## How to Run

1. Open the notebook in **Google Colab**.  
2. Run all cells sequentially from top to bottom.  
3. Review:
   - Interactive chat simulation  
   - Summarization after every k-th message  
   - Truncation examples  
   - Structured JSON extraction  
   - Conversation history persistence 




