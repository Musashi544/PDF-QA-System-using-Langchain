# PDF-QA-System-using-Langchain

This project is able to answer questions about topics that are in the pdfs.
 
Steps To Run 

<b>1. RUN OLLAMA USING COLAB GPU<b>
- Create a ngrok account to get Auth Token and Domain name 
- Clone the Repo
- Run the Running_Ollama.ipynb in colab to run ollama using ngrok to get a public url. After       Running 4th Cell you will get a public url.
- Copy the public url and create a path variable OLLAMA_HOST = public url you got

<b>2. DOWNLOAD LLAMA2<b>
- In command prompt run command to download llama2 - ollama run llama2 

<b>3. Running The Application<b>
- Add the pdf to pdfs folder
- Run notebook.ipynb. 
- Just add the public url in the variable "URL" in the notebook.