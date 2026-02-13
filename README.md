# 🐾 S.O.S Pets - Chatbot com IA para Apoio à Adoção Animal

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=00bfbf&height=200&section=header&text=S.O.S%20PETS&fontSize=80&animation=fadeIn">
</p>

## 📋 Sobre o Projeto

O **S.O.S Pets** é uma aplicação inteligente projetada para dar voz aos animais abandonados. Utilizando **IA Generativa** e **Visão Computacional**, transformamos fotos em campanhas de adoção profissionais, humanizadas e prontas para redes sociais.

> **"A tecnologia descreve, o amor adota."**

---

## 🎯 Objetivo Principal

Criar um sistema que permita a ONGs, protetores e cidadãos comuns descrever animais de forma atrativa e sensível, mesmo com pouco tempo ou recursos, aumentando significativamente as chances de uma adoção responsável.

---

## 🏆 Projeto Acadêmico

- Disciplina: Inteligência Artificial  
- Turma: BRSAO179  
- Grupo: 01 (S.O.S PETS)  
- Instituição: Escola da Nuvem & AWS re/Start  

---

## ✨ Características Principais

- IA Conversacional Humanizada com Amazon Bedrock (Claude Sonnet 4.0)
- Upload e análise de imagens
- Inferência automática de características do animal
- Geração de descrição para redes sociais
- Interface interativa em modo escuro
- Histórico de interações
- Filtro de segurança para animais silvestres

---

## 🏗️ Arquitetura Técnica

Tecnologias utilizadas:

- Frontend: Streamlit
- Backend: Python
- IA Engine: Amazon Bedrock
- Cloud: AWS EC2
- Metodologia Ágil: Kanban / Scrum (Trello)

---

## 📁 Estrutura do Projeto

```text
SOS-PETS/
├── app.py
├── functions.py
├── requirements.txt
├── run.sh
├── assets/
└── images/
```

---

## 🚀 Como Executar

### Pré-requisitos

- Python 3.8+
- Credenciais AWS configuradas
- Acesso ao Amazon Bedrock

### Instalação e execução

```bash
git clone https://github.com/rodrigo-srf/SOS-PETS.git
cd SOS-PETS

python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

pip install -r requirements.txt
streamlit run app.py
```

---

## 💬 Experiência do Usuário

Fluxo de interação humanizado:

**Início da conversa**
Oi! 😊 Eu sou da S.O.S Pets e estou aqui para ajudar você a encontrar um lar amoroso para esse pequeno!

**Interação**
- Solicitação sequencial de informações
- Linguagem simples e acolhedora
- Uso de emojis para facilitar a comunicação

**Classificação de segurança**
- Adoção comum: cães e gatos
- Alerta silvestre: orientação para órgãos ambientais

**Privacidade**
- Processamento seguro via AWS
- Dados utilizados apenas para geração do anúncio

---

## 📄 Licença

MIT License

---

## 👥 Equipe S.O.S PETS

Rodrigo Serafim   
Dayane Stefhany  
Brandon Lee  
Beatriz Lima  
Gabriel Carmo  
Jonas Oliveira  

---

<div align="center">
<img src="./images/logo_edn.jpeg" width="150"/>
<img src="./images/logo_aws.png" width="150"/>

<br><br>

<sub>"Transformando sinais em dados, e dados em decisões."</sub>
</div>
