## AI agents and python package manager (UV) installation

### Langchain 
* Install uv package manager frome https://docs.astral.sh/uv/getting-started/installation/
  inside working directory - uv init
* Create and activate virtual environment - uv venv  -> .venv\Scripts\activate
  in the root folder create requirements.txt :
    * langchain,
    * langchain_community,
    * langchain-openai,
    * langchain-groq,
    * python-dotenv,
    * langchain-google-genai

* uv add -r requirements.txt
* In root folder create .env ->  Create API keys in groq, openai, and google. 
* For jupyter notebook installation -> uv add ipykernel
