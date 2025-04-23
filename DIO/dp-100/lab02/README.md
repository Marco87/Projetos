# Criando um Chatbot Baseado em Conteúdo de PDFs

Este laboratório teve como objetivo a criação de um chatbot inteligente, capaz de responder perguntas com base em arquivos PDF fornecidos como base de conhecimento. A solução foi construída com recursos da nuvem Azure, utilizando ferramentas de IA generativa e busca semântica.

---

## Resource Group a Ser Utilizado

O **Resource Group** é o primeiro passo de qualquer projeto no Azure. Ele funciona como um agrupador lógico para todos os recursos relacionados ao experimento, facilitando o gerenciamento e a organização.

![Resource Group](https://github.com/user-attachments/assets/d4ce58d4-a82b-4c6d-bc40-92ed03b1bc8d)  
![Resource Group](https://github.com/user-attachments/assets/52a8207f-9e11-41fe-b90e-f550195d69c6)

---

## Criando o Hub do Azure AI Foundry

No Azure AI Foundry, criamos um hub que servirá como ambiente para upload, processamento e treinamento de nossos documentos. Esse hub centraliza os experimentos e recursos necessários para o desenvolvimento de soluções baseadas em IA generativa.

![Hub do Azure AI Foundry](https://github.com/user-attachments/assets/9d03d8b2-43d3-4828-9177-c63f9c9c34f4)

---

## Acessando o Foundry

Após a criação, acessamos o ambiente do Foundry para iniciar o processo de configuração dos modelos e ingestão de dados. A interface é amigável e permite a navegação entre os componentes do projeto de forma intuitiva.

![Acessando o Foundry](https://github.com/user-attachments/assets/9d484d36-e601-4087-8b0d-fc651f32257a)

---

## Criando os Modelos GPT-4 e Text Embedding

Foram configurados dois modelos fundamentais para o funcionamento do chatbot:

- **GPT-4o**: responsável por gerar respostas com linguagem natural.
- **Text Embedding 3 Large**: converte os textos dos PDFs em vetores numéricos que serão usados para buscas semânticas.

![Modelos GPT-4 e Embedding](https://github.com/user-attachments/assets/04e620f0-4c26-4419-9d90-4387b9ec2795)

---

## Fazendo o Upload dos Arquivos

Realizamos o upload de dois arquivos PDF com conteúdo sobre **tipos de temperamento**. Esses documentos serviram como fonte principal de dados para o treinamento do nosso chatbot.

![Upload de Arquivos](https://github.com/user-attachments/assets/fbe297ac-bbe4-4f6e-a291-49c06c11fc17)

---

## Criando o Azure AI Search

O serviço **Azure AI Search** foi configurado para fornecer uma camada de busca semântica. Ele possibilita que o chatbot encontre informações relevantes nos documentos com base na semelhança do conteúdo, e não apenas por palavras-chave.

![Azure AI Search](https://github.com/user-attachments/assets/24a724d2-3aa9-497d-b256-8a0d3eb6250d)

---

## Criação dos Vetores de Texto

Com os PDFs processados, o sistema extrai partes dos textos e os converte em vetores. Esses vetores são comparados com as perguntas feitas ao chatbot, permitindo uma resposta precisa baseada em contexto e significado.

![Vetores de Texto](https://github.com/user-attachments/assets/59247488-58d8-4db9-b3c4-3ee6bca0d4e2)

---

## Resposta à Pergunta Feita no Chat

Como teste final, foi feita uma pergunta simples ao chatbot solicitando a **descrição dos tipos de temperamento**. A resposta fornecida foi correta e baseada no conteúdo dos PDFs enviados, validando o sucesso do experimento.

![Resposta no Chat](https://github.com/user-attachments/assets/0b4f6fd0-9666-45fa-92c8-7f8272e7715d)

---

## Removendo o Resource Group

O Resource Group foi removido para evitar que os créditos da conta na Azure sejam usados sem necessidade.

![image](https://github.com/user-attachments/assets/8c2a3ad7-7515-4663-be8a-3f8a8629ec37)

---

## Principais recursos utilizados

- **Resource Group**: Agrupa e gerencia recursos relacionados a um projeto no Azure.
- **Azure AI Foundry**: Plataforma para experimentos de IA generativa, permitindo upload de dados, configuração de fluxos e deployment de modelos.
- **GPT-4o**: Modelo de linguagem avançado, utilizado para geração de respostas.
- **Text Embedding 3 Large**: Modelo que transforma texto em vetores semânticos para busca contextual.
- **Azure AI Search**: Serviço de busca inteligente que encontra conteúdos relevantes com base no significado das palavras.

---

**Autor:** Marco Aurélio Alencastro Pacheco

**LinkedIn:** [Marco Alencastro](https://linkedin.com/in/marco-alencastro)

**Data:** Abril/2025
