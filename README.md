# Care Connect AI 🏥🤖  
**AI-Powered Medical Assistant**

---

## 📌 Project Overview  
Care Connect AI is an intelligent **AI-powered healthcare assistant** designed to help users access reliable healthcare information and basic medical support. It leverages **Natural Language Processing (NLP)** and **machine learning** to understand user queries, provide medical insights, and assist patients with symptom checking, health recommendations, and connecting to doctors.  

The goal of this project is to **bridge the gap between patients and healthcare providers** by offering quick, accessible, and user-friendly medical guidance.

---

## 🚀 Features  
- ✅ Symptom-based medical suggestions  
- ✅ AI-driven chatbot interface  
- ✅ Integration with medical knowledge base  
- ✅ User-friendly web interface (Flask/React/Other)  
- ✅ Secure handling of patient queries  
- ✅ Future-ready: integration with telemedicine & wearable devices  

# How to run?
### STEPS:

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
PINECONE_API_KEY 
OPENAI_API_KEY 
```


```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
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

