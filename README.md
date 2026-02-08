# 🎤 Assistente de Voz Multi-Idiomas com Whisper e ChatGPT

Este projeto implementa um assistente de voz inteligente capaz de compreender perguntas faladas em diferentes idiomas, gerar respostas utilizando o ChatGPT e responder por voz utilizando Google Text-to-Speech (gTTS).

O sistema integra tecnologias modernas de IA para criar uma experiência de conversação natural e interativa.

---

## 🚀 Tecnologias Utilizadas

- Python
- OpenAI Whisper (Speech-to-Text)
- ChatGPT (OpenAI API)
- Google Text-to-Speech (gTTS)
- SoundDevice
- Google Colab (para prototipação)

---

## 🧠 Como Funciona

1. O usuário faz uma pergunta por voz 🎤  
2. O áudio é convertido em texto usando Whisper  
3. O texto é enviado para o ChatGPT  
4. A resposta gerada é convertida em áudio 🔊  
5. O usuário escuta a resposta falada  

---

## 📂 Estrutura do Projeto

```text
assistente-voz-multi-idiomas/
├── src/
├── notebooks/
├── requirements.txt
└── README.md
