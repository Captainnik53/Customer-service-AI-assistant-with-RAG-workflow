# Customer-service-AI-assistant-with-RAG-workflow

Live demo: https://nikunjgondha.app.n8n.cloud/webhook/5f1c0c82-0ff9-40c7-9e2e-b1a96ffe24cd/chat

Implementation details
1. N8N workflow where PDFs are uploaded to google drive
2. From google drive PDF data is downloaded and given to Pinecone Vector DB which stores embeddings using openai embeddings
3. OpenAI gpt-4o moodel is used as a wrapper to answer user questions which is directly connected to Vector store to get more context for providing answers

Invite link to view the workflow on n8n - https://nikunjgondha.app.n8n.cloud/signup?inviterId=73adb8e1-6492-4280-942e-f513d06a4fae&inviteeId=21b8baa9-eaf2-43e1-87f8-2bceb1a7017b

In case you are not able to access the invite link, refer to the JSON file, download and import in n8n workflows


Agent in Action

<img width="1279" alt="image" src="https://github.com/user-attachments/assets/1d12c0ff-1cfd-4df9-8934-250029457c84" />

<img width="1277" alt="image" src="https://github.com/user-attachments/assets/e9472c3f-9954-449d-9307-f9fb5b219f29" />

