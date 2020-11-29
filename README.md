# TextSimiliarity

## Overview

This project is to estimate the similarity between texts using Spacy, NLTK and Gensim.

## Structure

- src

    The source code to extract the features of the text and estimate the similarity.

- utils

    * The model to extract the features of each text.
    * The source code to manage the folder and file in this project.
    
- app

    The main execution file.
    
- requirements

    All the dependencies for this project.
    
- settings

    Several settings including the path of folders and files in this project.
    
## Installation

- Environment

    Ubuntu 18.04, Python 3.6
    
- Dependency Installation

    * Please go ahead this project directory and run the following commands
    
    ```
    pip3 install -r requirements.txt
    ```
  
    * Then please go ahead the directory where the Spacy framework is installed and run the following command.
    ```
    python3 -m spacy download en_core_web_sm
    ```

## Execution

- please go ahead project directory and run the following command.
    ```
        python3 app.py
    ``` 
 
