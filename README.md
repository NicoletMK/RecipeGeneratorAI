# 🍳 AI Recipe Generator

[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](recipe_generator.ipynb)
[![OpenAI API](https://img.shields.io/badge/OpenAI-API-412991)](https://platform.openai.com)

An intelligent recipe suggestion system powered by ChatGPT API, demonstrating prompt engineering techniques and Jupyter Notebook integration.

## 📖 Table of Contents
- [Features](#-features)
- [Prerequisites](#-prerequisites)
- [Installation](#-installation)
- [Usage](#-usage)
- [Customization](#-customization)
- [Project Structure](#-project-structure)
- [Best Practices](#-best-practices)
- [Example Output](#-example-output)
- [Acknowledgments](#-acknowledgments)
- [License](#-license)

## 🌟 Features
- **AI-Powered Recipe Generation** using ChatGPT 3.5-turbo
- Secure API key management with `.env` files
- Interactive Jupyter Notebook interface
- Role-based prompting and few-shot examples
- Error handling and loading states
- Markdown-formatted recipe output

## 🛠 Prerequisites
- Python 3.8+
- [OpenAI API key](https://platform.openai.com/api-keys)
- Jupyter Notebook/Jupyter Lab
- Required packages:
  ```bash
  openai>=1.0.0
  python-dotenv
  ipywidgets

## 📦 Installation
- Clone repository:
  ```bash
  git clone https://github.com/yourusername/ai-recipe-generator.git
  cd ai-recipe-generator
- Install dependencies:
  ```bash
  pip install -r requirements.txt
- Create .env file:
  ```bash
  OPENAI_API_KEY=your_api_key_here
- Launch Jupyter Notebook:
  ```bash
  jupyter notebook

## 🚀 Usage
Open Recipe_Generator.ipynb<br>
Run all cells (Kernel > Restart & Run All)<br>
Click the "Generate Recipe" button<br>
Watch AI create recipes in real-time!<br>

Custom Prompts:<br>
Modify system messages in the notebook<br>
Add few-shot examples for different cuisines<br>
Adjust temperature parameter (0.2-1.0)<br>

## 📂 Project Structure
.

├── .env                    # Environment variables

├── Recipe_Generator.ipynb  # Main notebook

├── README.md               # Documentation

├── requirements.txt        # Dependencies

└── .gitignore              # Ignore .env files<

## 🔑 Best Practices
Security: Never commit .env files
API Limits: Implement rate limiting for heavy usage
Testing: Use different temperature values
Validation: Add input validation for ingredients
Logging: Implement error logging

## 📝 Example Output
Simple Recipe: Recipe: Honey Garlic Shrimp

Ingredients:

1 pound shrimp, peeled and deveined
1/4 cup honey
2 cloves garlic, minced
Instructions:

In a bowl, mix together the honey and minced garlic until well combined.
Heat a skillet over medium heat and add the shrimp.
Cook the shrimp for 2-3 minutes on each side until they start to turn pink.
Pour the honey garlic mixture over the shrimp and stir to coat.
Continue to cook the shrimp for another 1-2 minutes until they are cooked through and the sauce has thickened.
Serve the honey garlic shrimp hot with your favorite side dish and enjoy!

