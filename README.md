# AI-FAQ-Chatbot

Complete Retrieval-Augmented Generation (RAG) pipeline

**Architecture**
Your pipeline is now:

User Question
      ↓
Retrieve Top 3 Documents
      ↓
Check Retrieval Distance
      ↓
Build System Prompt
      ↓
LLM (Streaming)
      ↓
Gradio Chat


**Interview Questions**
1 - Why did you choose n_results=1 instead of 3 or 5?
2 - What happens if retrieval returns an unrelated FAQ?
3 - Why did you store metadata separately from documents?
4 - What's the difference between cosine similarity and Chroma's nearest-neighbor search?
5 - Why use a vector database instead of a Python list?
6 - How would you support a dataset with one million FAQs?
7 - Why did you choose n_results=3? How would you decide between 3, 5, or 10?
8 - How would you detect when retrieval has failed and avoid sending irrelevant context to the LLM?
9 - Why embed both the question and the answer together instead of only the question?
10- What advantages does PersistentClient provide over an in-memory client?
11- How would you handle updates when FAQs change without rebuilding the entire collection?
