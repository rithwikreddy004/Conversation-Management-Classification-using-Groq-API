
# Conversation Management & JSON Extraction with Groq API

## Overview
This project demonstrates the use of Groq API for **managing conversational data** and performing **structured information extraction** from user chats. It covers two core tasks:

1. **Conversation Management with Summarization**  
   - Maintains a running conversation history of user–assistant interactions.  
   - Performs **periodic summarization** to keep conversations concise.  
   - Supports **customizable truncation** by number of turns or character length.  
   - Interactive demonstration allows feeding multiple conversation samples and observing summarization behavior.

2. **JSON Schema Classification & Information Extraction**  
   - Extracts structured user information such as name, email, phone, location, and age.  
   - Implements **OpenAI-compatible function calling** through Groq API.  
   - Supports interactive input for dynamic extraction.  
   - Validates outputs against a predefined JSON schema.

## Features
- **Interactive Demos**: Run conversations or user chats in Google Colab.  
- **Dynamic Truncation**: Limit conversation history by turns or characters.  
- **Periodic Summarization**: Summarizes after every k-th conversation turn.  
- **Structured Extraction**: Extracts relevant user information using JSON schema.  
- **Python Only**: No frameworks used; compatible with standard Python and OpenAI SDK.

## Getting Started
1. Clone the repository:  
   ```bash
   git clone https://github.com/rithwikreddy004/Conversation-Management-Classification-using-Groq-API.git
   cd Conversation-Management-Classification-using-Groq-API

