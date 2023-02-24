# GPT-Search
A Question Answering chatbot powered by GPT-3 answer synthesis and sentence-transformers sentence embeddings that can answer questions based on your own data. Here, we use a PDF file about superheroes and their evolution and influence on pop-culture. The knowledge from the PDF is fed into the bot so that the bot can later answer questions about it when asked.

Currently works with [FAISS](https://github.com/facebookresearch/faiss) but can easily be used with other vector DBs like qdrant, chroma, pinecone, etc for better scalability.

A Demo app can be found [here](https://huggingface.co/spaces/adirtha1903/CapedConversations/blob/main/app.py)
