# langchain-ask-pdf-gradio

## Why
Using langchain gets LLMs to pay attention to your content.

## How
Python project using a gradio interface to query an online pdf document using langchain

## Quickstart
Using a machine with python installed
Clone or download this repo

Make sure that python and virual environment is installed.
    
### Create a new virtual environment
    

#### one time
```
virtualenv -p $(which python3) pyenv
```

#### everytime you want to run the server
```
source pyenv/bin/activate
```

### Now install the requirements

```
pip install -r requirements.txt
```




Rename the .env-template file to .env 
Edit the .env file entering your OpenAI GPT API key (see below for details) after the equals sign on the first line

Run the application with the following command:
```
python app.py
```
This will output a url which can be used by a browser.
Entering a question and a url to a PDF available online should get you a syntactic-well-formed  semantic-related answer

## OpenAI API key
This can be found here:
https://platform.openai.com/login

After login or sign up you can find or create a new key under your account menu inn the upper right corner of the navigation bar. In the menu select "View API Key." This will redirect you to a screen where you can click on the "Create new secret key button." It is strongly recommended you create a new key for each application for which you use OpenAI GPT.
