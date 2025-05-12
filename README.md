# CHATBOT BASEADO EM CONTEÚDO DE PDFS NA AZURE


[![Azure](https://img.shields.io/badge/Azure-%230089D6.svg?logo=microsoft-azure&logoColor=white)](https://azure.microsoft.com/)  
  
Este repositório demonstra a implementação de um **chatbot inteligente** capaz de analisar conteúdo de PDFs e responder perguntas contextualizadas, utilizando serviços escaláveis da **Microsoft Azure**.  

---

## 📋 Visão Geral  
O projeto visa criar um chatbot que:  
1. Extrai texto de PDFs (incluindo OCR para documentos digitalizados).  
2. Processa e indexa o conteúdo em formato vetorial.  
3. Gera respostas precisas usando modelos de linguagem avançados.  
4. Opera em ambiente seguro e escalável na nuvem (Azure).  

**Aplicações Práticas**:  
- Suporte automatizado para manuais técnicos.  
- Consulta rápida em documentos jurídicos ou médicos.  
- Educação baseada em materiais didáticos em PDF.  

---

## 🚀 Funcionalidades Principais  
| Etapa               | Tecnologia Utilizada (Azure)           | Descrição                                                                 |  
|---------------------|----------------------------------------|---------------------------------------------------------------------------|  
| **Extrair Texto**   | Azure Form Recognizer                  | Extrai texto, tabelas e até assinaturas de PDFs complexos.                |  
| **Gerar Embeddings**| Azure OpenAI Service                   | Transforma o texto em vetores semânticos usando modelos como `text-embedding-ada-002`. |  
| **Busca Vetorial**  | Azure Cognitive Search (Vector Search) | Armazena e busca vetores para identificar trechos relevantes em milissegundos. |  
| **Gerar Respostas** | Azure OpenAI GPT-4                     | Produz respostas naturais e contextualizadas com base nos dados dos PDFs. |  
| **Interface**       | Azure Bot Service                      | Oferece uma UI de chat integrada ao Teams, WhatsApp ou web.               |  

---

## 🛠️ Configuração do Projeto  

### Pré-requisitos  
- Conta na [Azure](https://azure.microsoft.com/) com acesso a:  
  - **Azure Form Recognizer**  
  - **Azure OpenAI Service**  
  - **Azure Cognitive Search**  
- Python 3.10+ e `pip` instalados.  