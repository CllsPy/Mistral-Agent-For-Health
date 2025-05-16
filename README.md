# Health Agent with Mistral

![image](https://github.com/user-attachments/assets/361c5db8-6bac-49db-bb54-8b390c859f1a)

## 🧠 Project Overview

This project aims to create an intelligent agent capable of researching and writing an article based on a chosen topic. It leverages Mistral and other AI tools to automate content generation in a structured and coherent way.

## 🚀 How It Works

The project follows these main steps:

1. Install required libraries
2. Set up API access
3. Define AI agents and their roles
4. Format and output the generated article

## 📦 Requirements

* **Python**: A high-level, interpreted programming language.
* **IDE**: Any environment capable of running Python code, such as:

  * Google Colab
  * Jupyter Notebook

## 🔧 Installation & Dependencies

Make sure the following packages are installed before running the project:

```python
import os
from google.colab import userdata
from crewai_tools import SerperDevTool
from langchain_mistralai import ChatMistralAI
from crewai import Agent, Task, Crew, Process
```

## ▶️ Getting Started

1. Download the file `HAWM.ipynb`
2. Open it using your preferred IDE (Google Colab or Jupyter)
3. Follow the steps inside the notebook to run the agent

## 👥 Authors

*To be added.*

## 📄 License

This project is licensed under the MIT License.

## 🙏 Acknowledgements

Special thanks to Arin Brahma from Loyola Marymount University for providing the initial project structure and dataset.
