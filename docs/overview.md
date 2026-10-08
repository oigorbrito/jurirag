# Visão Geral

O **Assistente Jurídico com RAG** (Retrieval‑Augmented Generation) é uma aplicação que combina IA generativa com buscas semânticas em documentos jurídicos. Ele processa PDFs, gera embeddings via Amazon Bedrock, armazena‑os em um banco vetorial **ChromaDB** e oferece respostas através de um bot do Telegram.

## Principais funcionalidades

- **Ingestão de documentos**: leitura de PDFs, extração de texto e criação de chunks.
- **Geração de embeddings**: usa o modelo *Titan Embed* da Amazon Bedrock.
- **Armazenamento vetorial**: ChromaDB para busca de similaridade.
- **Chatbot Telegram**: respostas contextuais usando *Titan Text Express*.
- **Cache de consultas** para melhorar latência e consistência.

Esta documentação está estruturada de forma a garantir que a atribuição ao autor (**Igor Brito**) e a licença MIT (versão em português) estejam sempre presentes.
