
# 🧠 Sistema de Recuperação de Informações com VectorDB e RetrievalQA  

Este projeto implementa um sistema de **Perguntas e Respostas** utilizando vetores de embeddings e banco de dados vetorial com **FAISS**, integrado à biblioteca **LangChain**. Ele processa um texto extraído de uma página HTML, divide-o em chunks, gera embeddings e utiliza o módulo **RetrievalQA** para responder perguntas com base no conteúdo mais relevante.  

---

## 🚀 Funcionalidades  
✔️ **Extração de Texto**: Utiliza BeautifulSoup para extrair texto de páginas HTML.  
✔️ **Divisão em Chunks**: Segmenta o texto em partes menores para melhor contextualização.  
✔️ **Banco Vetorial**: Gera e armazena embeddings em um banco vetorial FAISS.  
✔️ **Respostas Inteligentes**: Responde perguntas usando o modelo **OllamaLLM** integrado ao RetrievalQA.  

---

## 📋 Pré-requisitos  
- **Python 3.8+**  
- Bibliotecas listadas no `requirements.txt`  

### 🔧 Instalação  
1. Clone este repositório:  
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio

   Instale as dependências:
   
2. Instale as dependencias:  
pip install -r requirements.txt

3. Como usar
Clone o repositório e instale as dependências listadas no requirements.txt.
Execute o script para criar o banco de dados vetorial e configurar o sistema de perguntas e respostas.
Faça perguntas relacionadas ao conteúdo e receba respostas precisas baseadas nos textos processados.

💡 Exemplo de Pergunta:
"O que é um gêmeo digital?"
Resposta: [Texto relevante do artigo
