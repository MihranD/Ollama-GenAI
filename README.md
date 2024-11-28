# Generative AI using Ollama
***
Open Source model running locally via Ollama

***
The project demonstrates two approaches to interact with the **Ollama** API for content extraction and summarization. First, the **requests API** is used to call the Ollama URL and process data. Then, the same task is accomplished using the **Ollama framework**, showing that both methods yield the same results, but with different implementation strategies. This highlights the versatility of Ollama in achieving content extraction and summarization through different approaches.

![Coach](https://github.com/MihranD/Ollama-GenAI/blob/main/images/coach.png)

## Project Organization
----------------------------------------------------------------------------------------------
    ├── .gitignore          <- Includes files and folders that we don't want to control
    |
    ├── images              <- Images for use in this project
    │   ├── coach.png           <- Coach image
    │   └── ollama-result.png   <- Ollama result image
    |
    ├── main.ipynb          <- Main jupyter file that needs to be run
    |
    ├── requirements.txt    <- The required libraries to deploy this project. 
    |                       Generated with `pip freeze > requirements.txt`
    └── README.md           <- The top-level README for developers using this project.

## Project Introduction

### Business Problem

Businesses struggle to efficiently extract and summarize valuable insights from vast amounts of unstructured web data, and this project provides an automated solution using the **Ollama API** and **framework**.

### Problem Definition

Extracting and summarizing relevant information from large volumes of unstructured web content is a time-consuming and manual process, leading to inefficiencies in businesses that need quick, actionable insights. This project aims to automate the process using the **Ollama API** and **framework** to generate accurate and concise summaries.

### Model Output Example

`messages = [
    {"role": "user", "content": "Describe key points of the coach in football macth strategy"}
]`

![Ollama result](https://github.com/MihranD/Ollama-GenAI/blob/main/images/ollama-result.png)

## Conclusion

Both the API approach and the local Ollama setup provide the same functionality in terms of interacting with Ollama models. However, using the **Ollama Python package**, rather than making direct HTTP calls, offers a more elegant and streamlined solution. The Python package simplifies the process by abstracting away the complexity of handling raw HTTP requests, making the code cleaner, more readable, and easier to maintain.

## How to run the app

Follow these steps to set up and run the application:

1. **Install Dependencies**  
   Run the following command to install all required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

2. **Open and Run the Notebook**  
   Open the `main.ipynb` file in Jupyter Notebook and execute the cells to run the application.
