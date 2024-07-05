Hello,
Here I will guide you on how to make use of this folder , files.

1. Firstly install VS studio code.
2. Set the directory as your folder name with command cd "folder_path"
2. Install all the packages in requirements.txt with command pip install -r requirements.txt  
3. Open the .env file which will ask you for langchain , cohereapi and openai which is setup as NA at this point of time. Enter the suitable keys 
You can also choose to change EMBEDDINGS_MODEL_NAME & MODEL_TYPE Between OpenAI & Llama3.
(If you wish to change it to model of your choice you have to change the model name condition in LLMtool.py (line 208)


 


4. Try installing other packages if you are facing issues with any other dependencies or package requirements.

5. Now our environment is set. Lets go to LLMTool.py file.
Try to look at the code and understand it very carefully.

6. If you run the the streamlit command with 
py -m streamlit run ‘your path’
For example:
“
py -m streamlit run "c:/Users/Satej Raste/Downloads/RAG Projects/LLM_tool.py"
“
You will be able to access the streamlit webpage.
You can select the browse option in teft pane which is called as “Browse files”, upload the files with permissible extensions.
Once you upload it , You will see a processing button which indicates the file is in processing state.
Once its done , go to the question pane and type in your questions.
If everything works fine then You will be able to see an output like the one mentioned below :

