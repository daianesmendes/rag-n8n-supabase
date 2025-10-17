\# 🤖 RAG Agent com Supabase e n8n



Projeto que integra um \*\*agente RAG\*\* (Retrieval-Augmented Generation) no \*\*n8n\*\*, usando \*\*Supabase PGVector\*\* como base vetorial e \*\*Google Drive\*\* para ingestão automática de conhecimento.



---



\## ⚙️ Estrutura



\### 🔴 RAG Agent

Fluxo que responde perguntas dos usuários com contexto vindo do Supabase.



\*\*Principais nós:\*\*

\- AI Agent (OpenAI)

\- Supabase Vector Store

\- Simple Memory

\- Embeddings OpenAI



\### 🟤 Knowledge Ingestion

Fluxo que atualiza o banco vetorial automaticamente quando novos arquivos são adicionados no Google Drive.



\*\*Principais nós:\*\*

\- Google Drive Trigger  

\- Extract from File (XLSX)  

\- Supabase Vector Store  

\- Embeddings OpenAI  



---



\## 🧠 Tecnologias

\- n8n.io  

\- OpenAI GPT \& Embeddings  

\- Supabase PGVector  

\- Google Drive API  



---



\## 🚀 Como usar

1\. Importe os arquivos `.json` na pasta `/workflows` no n8n.  

2\. Configure as credenciais: OpenAI, Supabase e Google Drive.  

3\. Teste enviando mensagens para o agente.



---



\## 👩‍💻 Autoria

Desenvolvido por \*\*Daiane Mendes\*\*  

Estagiária de IA e Automação – \[01 Tecnologia / Obra Prima](https://obraprima.com.br)



