# Automated_csv_profiler

## The purpose of the system:
* The purpose of this repo is to automate data analysis through a Python algorithm and then provide the result to an LLM for AI-assisted insight. The Python algorithm provides a JSON summary of the dataset's overview, data quality profile, descriptive statistics, and relationships between variables. The algorithm also provides adaptive visualizations. All of these outputs are then fed to LLM locally to provide AI-assisted insight.
  
## Python version used:
* Python 3.14.7

## Required libraries:
* pandas, numpy, matplotlib, json, os, seaborn, and requests

## Installation steps:
* Clone the repository, download and install Ollama in the terminal ("ollama pull qwen2.5:0.5b"), activate the virtual environment (".\mp02_env\Scripts\Activate.ps1"), and install the required libraries from requirements.txt
  
## Exact steps to run the program:
1. Open profiler.ipynb inside the src folder
2. Run all setup and function definition cells
3. Execute the call function with your desired CSV

## How to select a CSV file:
1. Upload your desired CSV inside the data folder
2. Execute the call function with the CSV path of your desired CSV

## How to enable or disable the LLM component:
* In the call function, make sure the "use_llm" parameter is "FALSE"

## Which model was used:
*qwen2.5:0.5b using local ollama api

## Known limitations:
1. Only one-table CSV files are supported
2. Sensitive data tag replies based on specific keywords in the column name only
3. The LLM isn't perfect with its response in terms of correctness or format.

## Sources for both public datasets:
