# Algorithm Identification Using AI

## Overview
This project explores the use of artificial intelligence to identify sorting algorithms implemented in C functions. Various open-source AI models were evaluated for their precision, execution speed, and response consistency.

## Features
- **Automated Testing**: A Python script evaluates AI models on C functions.
- **Prompt Optimization**: Improved interaction with AI models for better results.
- **Comparative Analysis**: Benchmarked several models, including Falcon, Mistral, and Llama.
- **Result Logging**: Outputs stored in an Excel file for further analysis.

## Technologies Used
- **Language**: Python
- **Key Libraries**:
  - [OpenPyXL](https://openpyxl.readthedocs.io/en/stable/): For Excel file manipulation.
  - [LangChain Ollama Integration](https://python.langchain.com/docs/integrations/llms/ollama/): For interaction with AI models.
  - `sqlite3`, `os`, and `time`: For database handling and performance measurement.

## Key Results
- **Best Model**: Falcon3:7B, offering the best balance of accuracy and speed.
- **Execution Time**: Ranged from 672s to 2575s depending on the model.
- **Response Consistency**: Highlighted variations in AI outputs across multiple runs.

## Installation and Usage
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/chaisebasse/Recherche_IA_algo.git
   cd Recherche_IA_algo
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
3. **Install AI Model from Ollama**
   ```bash
   ollama run llama3.1
4. **Run the Main Script**:
    ```bash
    python main.py

## Author
## Author
- **Ermanno di Giulio**  
  Second Year Undergraduate student in a dual degree program in **Economics-Management** and **MIASHS** (Mathematics and Computer Science), *Université Paris Nanterre*.
