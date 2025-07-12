# ShopAssist 2.0 – Enhanced Conversational AI with Function Calling

## 🚀 Overview

**ShopAssist 2.0** is an enhanced version of the original ShopAssist AI chatbot designed to create seamless, efficient, and intelligent customer interactions using OpenAI’s Function Calling API. This project aims to simplify the chatbot’s architecture by reducing redundant layers and introducing a more structured, maintainable, and intelligent design.

---

## 🧩 Problem Statement

While ShopAssist AI was effective in assisting users through natural language interactions, the system required multiple layers to manage intent clarity and enforce standardization for function execution. This layered design, although functional, led to complexity and inefficiency.

The core challenges addressed in ShopAssist 2.0:
- Redundant architectural layers for intent processing and standardization
- Complexity in ensuring consistent output format from the LLM
- Difficulty in extending chatbot functionalities seamlessly

---

## 🎯 Objective

Enhance the existing ShopAssist AI by integrating OpenAI's Function Calling capability to:
- Simplify the architecture
- Improve interaction quality and consistency
- Enable the chatbot to invoke structured API calls based on user intent

---

## 🛠️ Features

- ✅ **Function Calling Integration**: Connects OpenAI GPT to external APIs in a structured and reliable way
- ✅ **Streamlined Architecture**: Removes the multi-layered workaround for output formatting
- ✅ **Refined Conversation Flow**: Creates smoother and more natural dialogues with users
- ✅ **Personalized Recommendations**: Dynamically fetches and displays relevant data
- ✅ **Modular Design**: Easily extendable for new intents and functionalities

---

## 🧪 Tech Stack

- Python 🐍
- Jupyter Notebooks (`.ipynb`)
- OpenAI GPT-4 Function Calling
- LangChain (optional for chaining calls)
- JSON Schema for API interface
- Any external APIs or mock data (for demo purpose)

---

## 📁 Project Structure



## Approach
1. **Conversation and Information Gathering**: 
   - The chatbot uses language models to understand and generate natural responses.
   - Collects user preferences (e.g., budget, specifications, brand).
2. **Information Extraction**:
   - Employs rule-based functions to parse the dataset and extract the top laptops matching the user's criteria.
3. **Personalized Recommendation**:
   - Provides recommendations while maintaining a conversational flow to address user queries and refine choices.

## Technologies Used
- **Programming Language**: Python
- **Libraries and Tools**:
  - Pandas: For dataset processing.
  - OpenAI: For large language model interactions.
  - Function Calling API: For structured and efficient chatbot functionality.

## Getting Started
### Prerequisites
- Python 3.8 or later
- API key for OpenAI (set as an environment variable: `OPENAI_API_KEY`)
- Dataset containing laptop details in `.csv` format.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ravikirankrishnaprasad/ShopAssist2.0.git
   cd ShopAssist2.0
