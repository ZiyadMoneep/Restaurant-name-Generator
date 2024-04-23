# Restaurant Generator App

## Overview
The **Restaurant Generator App** is an innovative tool designed to inspire entrepreneurs and culinary enthusiasts by generating unique restaurant names and corresponding menu items based on linguistic inputs. Leveraging the power of OpenAI's API, LangChain, and state-of-the-art Large Language Models (LLMs), this app provides creative and culturally relevant suggestions tailored to user preferences. Built with Streamlit, the app offers a user-friendly interface that makes the generation process both interactive and enjoyable.

## Features
- **Restaurant Name Generation**: Generate unique and catchy restaurant names based on specified languages.
- **Menu Item Generation**: Create interesting menu items that complement the restaurant's concept.
- **Custom Language Input**: Users can choose specific languages to tailor the suggestions.
- **Interactive UI**: Streamlit-based interface for ease of use and immediate feedback.

## Installation

To set up the Restaurant Generator App on your local machine, follow these steps:

### Prerequisites
- Python 3.8 or later
- pip3

### Clone the Repository
```bash
git clone git@github.com:ZiyadMoneep/Restaurant-name-Generator.git
cd Restaurant-name-Generator
```

### Install Dependencies
```bash
pip3 install -r requirements.txt
```

### crerate and Add your .env file
```bash
touch .env
```

### put in .env file OPENAI_API_KEY as well as SERPAPI_KEY
```bash
OPENAI_API_KEY = "your openai key"
SERPAPI_KEY = "your key"
```

### Run the Application
```bash
python3 -m streamlit run main.py
```

After running the command, the Streamlit application will open in your default web browser.

For more information or questions feel free to contact me..

## MIT License

Copyright (c) - [Gamal Moneep](zmoneep.xyz)
