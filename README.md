# Build a Complete Medical Chatbot with LLMs LangChain Pinecone Flask AWS

Medibot AI is an intelligent medical assistant that uses **Retrieval-Augmented Generation (RAG)** to provide accurate, context-based answers to health-related questions.  
It combines **LangChain**, **Pinecone**, and **Gemini (Google Generative AI)** within a **Flask** framework to deliver fast and reliable chatbot responses.

---

# How to run?

### STEPS:

Clone the repository

```bash
git clone https://github.com/Vishvas810/medibot-ai.git
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```

### STEP 02- install the requirements

```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your Pinecone & openai credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the flask application
python app.py
```

Then, open your browser and navigate to:

```bash
http://127.0.0.1:8080/
```

### Demo

[▶️ Watch the Demo](assets/demo.mp4)

### Techstack Used:

- Python
- LangChain
- Flask
- Gemini
- Pinecone
