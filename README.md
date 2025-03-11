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
1. Clone repository:
  ```bash
  git clone https://github.com/yourusername/ai-recipe-generator.git
  cd ai-recipe-generator
2. Install dependencies:
  ```bash
  pip install -r requirements.txt
3. Create .env file:
  ```bash
  OPENAI_API_KEY=your_api_key_here
4. Launch Jupyter Notebook:
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
.<br>
├── .env                    # Environment variables<br>
├── Recipe_Generator.ipynb  # Main notebook<br>
├── README.md               # Documentation<br>
├── requirements.txt        # Dependencies<br>
└── .gitignore              # Ignore .env files<br>

## 🔑 Best Practices
Security: Never commit .env files<br>
API Limits: Implement rate limiting for heavy usage<br>
Testing: Use different temperature values<br>
Validation: Add input validation for ingredients<br>
Logging: Implement error logging<br>

