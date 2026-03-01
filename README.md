# Government-Scheme-Explainer-Chatbot

AP Government schemes such as Scholarship for students, welfare programs for farmers, women etc… are designed for people. But many people struggle to access and benefit from them.

# Main challenges include:

 Schemes are written in legal language – hard to understand.
 
 All the schemes data is scattered across multiple sources.
 
 Official documents and articles are lengthy – people have less time & patience to read.
 
 Users need direct answers to specific questions (Eligibility, required documents).

# What does this Chatbot do?

This chatbot will give information of schemes

Answer the queries of the user in simple language.

Gives Up to date information due to implementation of RAG workflow.

# RAG Workflow

1️⃣ User question → embedding 

2️⃣ Search in Vector DB (FAISS)

3️⃣ FAISS finds top matching chunks from PDFs

4️⃣ Retrieved text and question injected into prompt

5️⃣ Prompt is sent to LLM

6️⃣ LLM generates answers to user questions in simple language



