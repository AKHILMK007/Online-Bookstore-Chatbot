# Online-Bookstore-Chatbot

This project demonstrates a chatbot system using LangChain and OpenAI's GPT-3.5 architecture to enable natural language queries on an online bookstore database. The system leverages LangChain's utilities and chains, as well as T5-based text-to-SQL generation to interact with a MySQL database containing information about books. 

## Table of Contents

1. [Overview](#overview)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [License](#license)
7. [Acknowledgements](#acknowledgements)

## Overview

The project uses a Chatbot to interact with an online bookstore database. Users can ask questions in natural language, and the chatbot translates these queries into SQL commands to fetch information from the database.

## Prerequisites

Before you start, make sure you have the following installed:

- Python 3.8 or higher
- MySQL database server
- [OpenAI API key](https://beta.openai.com/signup/)
- Python packages listed in `requirements.txt` (refer to [Installation](#installation))

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/online-bookstore-chatbot.git
   cd online-bookstore-chatbot


## Create a virtual environment (optional but recommended):
 ```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
```

## Install the required packages:
 ```bash
pip install -r requirements.txt
```

## Set up the MySQL database:
Create a MySQL database named OnlineBookStore.
Create a table named Books in the OnlineBookStore database.
Populate the Books table with your data.
Update the database connection settings in your code (e.g., host, port, username, password).

## Get an OpenAI API key and set it as an environment variable:
```bash
export OPENAI_API_KEY=your_openai_api_key
```
