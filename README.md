# LLM-Driven Travel Planner ✈️🤖

An intelligent travel assistant powered by Large Language Models (LLMs) that helps plan trips by finding optimal flights and hotels through natural conversation.

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)



## Key Features 🌟

- **Conversational Interface**: Natural language interaction using state-of-the-art LLMs
- **Flight Search**: Real-time flight pricing and availability from Skyscanner API
- **Hotel Search**: Hotel recommendations based on travel dates and preferences
- **Budget Awareness**: Cost considerations for trip planning
- **Multi-API Integration**: Combines multiple travel APIs for comprehensive results

## Technology Stack 🛠️

- **Core LLMs**:
  - Hermes-3-Llama-3.2-3B (NousResearch)
  - Granite-3.1-3B (IBM)
- **APIs**:
  - Skyscanner Flight/Hotel Search API
  - RapidAPI integration
- **Libraries**:
  - Transformers (Hugging Face)
  - Outlines (JSON schema enforcement)
  - PyTorch
  - ipywidgets

## Installation 💻

1. Clone repository:
git clone https://github.com/yourusername/llm-travel-planner.git
cd llm-travel-planner

# Usage 🚀

## Start Jupyter Notebook:
jupyter notebook travel.ipynb

## Example interaction:
Bot: Hi! I'm your travel assistant. How can I help you today?
You: I want to go to Paris next month
Bot: Great choice! When would you like to travel?...


#Limitations & Future Work 🔮


##Current limitations:

Limited hotel API response handling

information extraction by LLM may not always produce accurate or consistent results

Basic date parsing implementation

Single traveler focus

##Planned improvements:

🧳 Multi-city trip support

💸 Advanced budget optimization

🌍 Local attraction recommendations

📅 Calendar integration
