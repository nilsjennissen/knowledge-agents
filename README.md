# 🧭 Project Overview

Welcome to the knowledge-agents project! In this project, we focus on adding contextual knowledge and data with txt, csv, and other document formats to Large Language Models like OpenAI's GPT-4. We leverage the LangChain library and deliver text and voice assistants for local data sources, making it easier for users to interact with and extract insights from their data. Inspirations for this repository are the LangChain library documentation and the LangChain Cookbook (see References).

## 🚧 Prerequisites

Before you start working on the project, make sure you have the following:

- Python 3.10 installed
- Basic knowledge of Python programming
- Familiarity with LangChain library (optional but recommended)

## 🎛 Project Setup

1. Clone the repository to your local machine:

```
git clone https://github.com/user/knowledge-agents.git
```


## 📦 Project Structure

Here's a brief overview of the project:
```bash
─kwoledge_agents/                           # Project folder
├── agent.py                                # Agent class
├── credentials.py                          # API credentials
├── data/                                   # Data folder
│   └── directory.csv                       # Sample data file of a repository
├── dir_csv.py                              # Create a csv file from a directory
├── glob_csv.py
├── models/
├── notebooks/                              # Jupyter notebooks
│   ├── simple_csv_loader.ipynb                   # Data agents notebook
│   └── knowledge_agents.ipynb              # Knowledge agents notebook
├── README.md                               
└── requirements.txt
```

## 🗄️ Data

The project provides a sample `directory.csv` file as a starting point. However, you can replace it with your own data files in CSV, TXT, or other formats to unlock the potential of the LangChain library and the Large Language Model. Make sure you update the data file paths in the relevant scripts.

## 📚 References

Most helpful resources and inspirations for this project:

- [LangChain library](https://python.langchain.com/en/latest/index.html)
- [LangChain Cookbook by gkamradt ](https://github.com/gkamradt)

## 🏆 Conclusion

This project enables users to interact with their data sources using text and voice interfaces powered by large language models and the LangChain library. Start building and testing the project to harness the power of these language models for your own data!

## 🤝 Contributions

Contributions are welcome! If you'd like to improve the project or add new features, feel free to fork the repository, make your changes, and submit a pull request. Please follow good coding practices and respect the project structure.