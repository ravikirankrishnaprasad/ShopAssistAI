# ShopAssist AI 2.0

## Introduction
ShopAssist AI 2.0 takes the original ShopAssist AI to the next level by integrating the **Function Calling API** for a more streamlined and efficient conversational experience. This enhanced chatbot leverages cutting-edge AI capabilities to provide personalized and accurate laptop recommendations, revolutionizing the online shopping experience.

## Project Background
With the rapid growth of e-commerce, online shopping has become the preferred choice for many. However, the sheer volume of options and lack of tailored assistance often leave consumers overwhelmed. ShopAssist AI 2.0 addresses these challenges by combining the power of **large language models** and **rule-based functions**, delivering an intelligent and user-centric shopping assistant.

## Problem Statement
The project focuses on building a chatbot that:
- Processes a dataset containing detailed information about laptops (product names, specifications, descriptions, etc.).
- Provides accurate and personalized laptop recommendations tailored to user requirements.
- Ensures an efficient, conversational, and user-friendly experience.

## Features
- **Function Calling Integration**: Improved architecture leveraging Function Calling API for better performance and reduced complexity.
- **Enhanced Conversation Flow**: Natural and dynamic interactions with users.
- **Laptop Recommendations**: Provides top-3 laptop recommendations based on user preferences.
- **Personalized Assistance**: Engages in dialogue to refine suggestions and address queries effectively.

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
