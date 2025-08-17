# AI-Powered Medical Chatbot

# PROCESS TO RUN APP
### STEPS:

Clone the repository

```bash
Project repo: https://github.com
```
### STEP 1 - Create a conda environment after opening the repository

```bash
conda create -n medicalchatbot python=3.10 -y
```

```bash
conda activate medicalchatbot
```


### STEP 2 - Install the requirements
```bash
pip install -r requirements.txt
```

### STEP 3 - Create a `.env` file in the root directory and add your Pinecone & OpenAI credentials as following:
```ini
PINECONE_API_KEY = "XXXXXXXXXXXXXXXXXXXX"
OPENAI_API_KEY = "XXXXXXXXXXXXXXXXXXXX"
```


```bash
# Run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command for chatbot app
python app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Flask
- GPT
- Pinecone