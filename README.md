# Assistente-de-voz-via-ChatGPT

ChatGPT Voice Assistant 
Um sistema que integra tecnologias de voz para texto e texto para voz para permitir uma conversa com o ChatGPT utilizando apenas a fala e com suporte a múltiplos idiomas,  integrando com Whisper (OpenAI) utilizando 
Python e JS.Foi utilizado como base as orientações do curso GenAI Dados - DIO/Bradesco.



# 📌 Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de criar uma experiência interativa onde o usuário pode:

* Fazer perguntas por voz
* Receber respostas inteligentes do ChatGPT
* Ouvir as respostas em áudio



# 💻Tecnologias Utilizadas

Whisper
-> Modelo de reconhecimento de fala para converter áudio em texto (Speech-to-Text)

ChatGPT (API da OpenAI)
-> Responsável por gerar respostas inteligentes

Google Text-to-Speech (gTTS)
-> Converte o texto gerado em áudio (Text-to-Speech)

Google Colab
-> Ambiente de execução do projeto



# ⚙️ Como Funciona

O sistema segue o seguinte fluxo:

Áudio do usuário
↓
Whisper (Speech-to-Text)
↓
Texto da pergunta
↓
ChatGPT (processamento da resposta)
↓
Texto da resposta
↓
gTTS (Text-to-Speech)
↓
Áudio da resposta



# 🧠 Funcionalidades

✔ Conversão de voz em texto
✔ Integração com IA para geração de respostas
✔ Conversão de texto em áudio
✔ Suporte a múltiplos idiomas
✔ Execução simplificada via Colab



# 📂 Estrutura do Projeto

📁 projeto/
 ┣ 📄 notebook.ipynb
 ┣ 📄 README.md
 ┗ 📁 assets/
     ┗ imagens e exemplos



# ▶️ Como Executar

1. Acesse o notebook no Google Colab
2. Instale as dependências necessárias
3. Configure sua chave da API da OpenAI
4. Execute as células do notebook
5. Grave um áudio 



# 🔐 Requisitos

Conta no OpenAI com API Key
Conta Google (para usar o Colab)
Conexão com internet



# 🎯 Objetivo

Demonstrar, de forma prática, como combinar diferentes tecnologias de IA para criar soluções interativas baseadas em voz.

# 📓 Notebook do Projeto

🔗 Visualizar no GitHub:  
[Notebook](./notebook.ipynb)

🚀 Abrir no Google Colab:  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mzGVJM1XVvzFcClvXcFACM-fSHthQn8e?usp=sharing)

# 👩‍💻 Autora
Jamille Rozinelli
