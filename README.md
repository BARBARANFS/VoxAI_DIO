# 🎙️ VoxAI

<p align="center">
<strong>Assistente de Voz Inteligente com Inteligência Artificial Generativa</strong>
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![Whisper](https://img.shields.io/badge/Whisper-Speech--to--Text-success)
![NLP](https://img.shields.io/badge/NLP-Natural%20Language%20Processing-purple)
![AI](https://img.shields.io/badge/Generative-AI-red)
![License](https://img.shields.io/badge/License-MIT-green)

</p>

---

# 📌 Sobre o Projeto

O **VoxAI** é um assistente de voz desenvolvido em Python que integra tecnologias modernas de **Processamento de Linguagem Natural (NLP)**, reconhecimento automático de fala e Inteligência Artificial Generativa.

A aplicação captura comandos de voz do usuário, converte o áudio em texto utilizando o modelo **Whisper**, interpreta a pergunta por meio de modelos da **Hugging Face** e gera uma resposta que é convertida novamente em áudio utilizando o **Google Text-to-Speech (gTTS)**.

O projeto foi desenvolvido durante o **Bootcamp Bradesco – IA Generativa e Dados**, promovido pela **Digital Innovation One (DIO)**, sendo adaptado para utilização com modelos locais da Hugging Face.

---

# 🚀 Executar no Google Colab

Você pode abrir e executar este projeto diretamente no Google Colab.

<p align="center">

<a href="https://colab.research.google.com/github/BARBARANFS/VoxAI_DIO/blob/main/VoxAI_DIO.ipynb" target="_blank">
<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

</p>

---

# 🔗 Acesso Rápido

### 📘 Notebook no GitHub

https://github.com/BARBARANFS/VoxAI_DIO/blob/main/VoxAI_DIO.ipynb

### 🚀 Executar no Google Colab

https://colab.research.google.com/github/BARBARANFS/VoxAI_DIO/blob/main/VoxAI_DIO.ipynb

---

# 🌟 Por que este projeto é relevante?

O VoxAI demonstra a integração entre diferentes áreas da Inteligência Artificial em uma única aplicação.

Entre seus principais diferenciais estão:

- 🎙️ Reconhecimento automático de fala (Speech-to-Text)
- 🧠 Processamento de Linguagem Natural (NLP)
- 🤖 Inteligência Artificial Generativa
- 🔊 Conversão de texto em áudio (Text-to-Speech)
- 📚 Utilização de modelos pré-treinados da Hugging Face
- 🐍 Desenvolvimento completo em Python

Mais do que um assistente de voz, o projeto demonstra uma pipeline completo de interação homem-máquina baseada em linguagem natural.

---

# 🎯 Objetivos

O projeto foi desenvolvido para explorar tecnologias modernas de IA aplicadas à interação por voz.

Os principais objetivos foram:

- Capturar comandos de voz.
- Converter áudio em texto.
- Interpretar perguntas utilizando IA.
- Gerar respostas contextualizadas.
- Converter respostas em áudio.
- Demonstrar aplicações práticas de NLP.

---

# 🚀 Funcionalidades

- 🎙️ Captura de áudio utilizando Google Colab
- 📝 Conversão automática de voz em texto com Whisper
- 💬 Interpretação de perguntas utilizando Hugging Face Transformers
- 🤖 Geração de respostas inteligentes
- 🔊 Conversão da resposta em áudio utilizando Google Text-to-Speech
- 💻 Execução em ambiente Jupyter Notebook

---

# 🏗️ Arquitetura da Solução

```text
+-------------+
|   Usuário   |
+-------------+
       │
       ▼
+----------------------+
| Captura de Áudio     |
+----------------------+
       │
       ▼
+----------------------+
| Whisper              |
| Speech-to-Text       |
+----------------------+
       │
       ▼
+----------------------+
| Texto Transcrito     |
+----------------------+
       │
       ▼
+----------------------+
| Hugging Face         |
| Transformers         |
+----------------------+
       │
       ▼
+----------------------+
| Resposta da IA       |
+----------------------+
       │
       ▼
+----------------------+
| Google gTTS          |
| Text-to-Speech       |
+----------------------+
       │
       ▼
+----------------------+
| Áudio Final          |
+----------------------+
```

---

# 🔄 Fluxo de Funcionamento

```text
Usuário
   │
   ▼
Grava comando de voz
   │
   ▼
Whisper realiza a transcrição
   │
   ▼
Pergunta em texto
   │
   ▼
Modelo Hugging Face interpreta o contexto
   │
   ▼
Resposta em linguagem natural
   │
   ▼
Google Text-to-Speech (gTTS)
   │
   ▼
Áudio reproduzido ao usuário
```

---

# 🛠️ Tecnologias Utilizadas

## Linguagem

- Python

## Inteligência Artificial

- Hugging Face Transformers
- Whisper
- Torch

## Processamento de Linguagem Natural

- NLP
- Speech-to-Text
- Question Answering

## Conversão de Áudio

- Google Text-to-Speech (gTTS)

## Ambiente

- Google Colab
- Jupyter Notebook

---

# 📂 Estrutura do Projeto

```text
VoxAI_DIO/
│
├── VoxAI_DIO.ipynb
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# ⚙️ Instalação

Clone o repositório:

```bash
git clone https://github.com/BARBARANFS/VoxAI_DIO.git
```

Entre na pasta do projeto:

```bash
cd VoxAI_DIO
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

---

# ▶️ Como Executar

Abra o notebook utilizando o Jupyter Notebook:

```bash
jupyter notebook
```

ou execute diretamente no **Google Colab** através do botão disponível neste README.

Abra o arquivo:

```text
VoxAI_DIO.ipynb
```

---

# 📦 Dependências

```text
transformers==4.40.0
torch==2.2.0
gtts==2.5.4
click==8.1.7
jupyter
notebook
```

---

# 💼 Competências Demonstradas

Durante o desenvolvimento deste projeto foram aplicados conhecimentos em:

## Inteligência Artificial

- IA Generativa
- Hugging Face Transformers
- Whisper
- Modelos Pré-treinados

## Processamento de Linguagem Natural

- NLP
- Speech Recognition
- Speech-to-Text
- Question Answering
- Text-to-Speech

## Desenvolvimento

- Python
- Google Colab
- Jupyter Notebook
- Git
- GitHub

## Engenharia de Software

- Organização de Projetos
- Documentação Técnica
- Estruturação de Pipelines de IA

---

# 🚀 Próximas Evoluções

O projeto possui potencial para futuras melhorias, como:

- Interface gráfica em Streamlit
- Execução totalmente local
- Integração com modelos LLM mais avançados
- Histórico de conversas
- Assistente de voz em tempo real
- Suporte multilíngue
- API REST

---

# 📄 Licença

Este projeto está licenciado sob a licença **MIT**.

---

# 👩‍💻 Autora

**Barbara Freitas **

Graduanda em Ciência de Dados

Projetos em Inteligência Artificial • IA Generativa • Machine Learning • Python

🔗 GitHub: https://github.com/BARBARANFS
