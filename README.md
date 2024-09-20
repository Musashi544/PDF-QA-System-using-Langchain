# PDF-QA-System-using-Langchain

Steps To Run 

1. Create a ngrok account to get Auth Token and Domain name 
2. Clone the Repo
3. Run the Running_Ollama.ipynb in colab to run ollama using ngrok to get a public url. After Running 4th Cell you will get a public url.
4. Copy the public url and create a path variable OLLAMA_HOST = public url you got
5. In command prompt run command
    - ollama run llama2 
   This will download llama2 
6. Now you are set to run notebook.ipynb. Just add the public url in the variable URL in the notebook.