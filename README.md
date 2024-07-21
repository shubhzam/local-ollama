# Computer Market Hub- AI intern Assignment

## Install ollama
### Go to www.ollama.com/download 
### Download ollama for your respective OS and have it running

## Llama-3 Setup
### Go to your terminal type the following = 'ollama pull llama3'
### It will download LLAMA-3 locally in your computer

## Requirements
### Run the requirement.txt before running the application

## Use python app.py to run the application

## Once the application is up:
### Go to postman/insomnia/thunderclient -> POST http://localhost:8080/pdf -> Select Body -> form-data  
### Select key = 'file' and type = file. Set value by uploading Corpus.pdf
### Click on Send

### Once uploading the pdf, go to  POST http://localhost:8080/ask_pdf ->Select Body -> raw
### Type your question in JSON format with key = query and value = question you want to ask?
### example =
##### {
#####    "query" : "Tell me about Jessup Cellars."
##### }
### Click on Send

## Response will be generated.  