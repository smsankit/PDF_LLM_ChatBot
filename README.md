# PDF Search ChatBot

**Intractive PDF chatBot Using following:**
- Python 3.8 
- Streamlit
- Langchain
- Google PaLM LLM Model
- FAISS Vector Store
- PaLM embadding
- Recursive text splitter

**Setup Instructions  -**
- Execute below command to install required package 
  pip install streamlit python-dotenv langchain PyPDF2 faiss-cpu langchain_google_genai google-generativeai langchain-community

- Create a Goolge API KEY and store it in System environment variable

**Deployment Instructions -** 
- Use below command to run the app
  streamlit run app.py

- Chat Bot will open in web browser

**User Instruction -** 
Upload and process the PDF file from side menu and then ask your questions

**Security and Performance -** 
- Put and read the sensitive info(Google API KEY) in the environment variable
- Use FAISS store for efficient storage  and fast query response
- Google PaLM help to refine and imporve the query accurace 


**High Level Diagram -** 
![alt text](LLM_HL_Arch_Diagram.jpg)
