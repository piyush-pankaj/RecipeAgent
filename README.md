
# Thai Recipe Agent 

## Overview  
The **Thai Recipe Agent Platform** is an AI-powered assistant built using **IBM Cloud** and **IBM Watsonx Orchestrate**. Its purpose is to help users discover **authentic Thai recipes** from a curated knowledge base. The agent provides meal suggestions, cooking instructions, and cultural context to make Thai cuisine accessible and enjoyable.  

---

## Features ✨  
- 🔍 **Recipe Discovery**: Search authentic Thai recipes from the knowledge base.  
- 🍲 **Meal Suggestions**: Get alternatives for breakfast, lunch, and dinner.  
- 🌍 **Cultural Context**: Learn about the origins and traditions behind Thai dishes.  
- 🛠️ **Powered by IBM Watsonx Orchestrate**: Uses orchestration flows to manage recipe queries and responses.  
- ☁️ **IBM Cloud Integration**: Secure, scalable hosting and data management.  

---

## Architecture 🏗️  
1. **Knowledge Base**: Curated Thai recipes stored in IBM Cloud services.  
2. **Watsonx Orchestrate Agent**: Handles user queries, orchestrates workflows, and delivers recipe recommendations.  
3. **User Interface**: CLI or web-based interface for interacting with the agent.  
4. **Integration**: Can connect with external recipe files (e.g., PDFs, Google Drive, OneDrive).  

---

## Setup ⚙️  
### Prerequisites  
- IBM Cloud account  
- Access to IBM Watsonx Orchestrate  
- Python 3.9+ (for local testing)  
- GitHub repository clone  

### Installation  
```bash
# Clone the repository
git clone https://github.com/piyush-pankaj/RecipeAgent.git
cd RecipeAgent

# Install dependencies
pip install -r requirements.txt
```

### Run the Agent  
```bash
python agent.py
```

---

## Usage 🍴  
- Start the agent and ask:  
  - “Find me a recipe for Pad Thai.”  
  - “Suggest a Thai dessert.”  
  - “Show me vegetarian Thai options.”  
- The agent will return recipes with ingredients, steps, and cultural notes.  

---

## Example Interaction 💬  
**User**: “I want a Thai curry recipe.”  
**Agent**: “Here are three authentic options:  
1. Green Curry (Gaeng Keow Wan)  
2. Red Curry (Gaeng Daeng)  
3. Massaman Curry (Gaeng Massaman)”  

---

## Future Enhancements 🚀  
- Add voice interaction.  
- Expand knowledge base with regional Thai specialties.  
- Generate grocery lists based on selected recipes.  
- Support multi-language queries (English, Thai, Hindi).  

---

## Disclaimer ⚠️  
This agent provides recipe recommendations for educational and culinary purposes.  
**Please consult a professional nutritionist or chef for dietary advice.**  

---

## Contributors 👩‍💻  
- **Piyush Pankaj** – Project Lead  
- Built with support from **IBM Cloud** and **IBM Watsonx Orchestrate**  

