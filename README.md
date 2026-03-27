# Reconhecimento de Fala em Áudio

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white) ![Topic](https://img.shields.io/badge/Topic-speech-recognition-green) ![License](https://img.shields.io/badge/License-MIT-yellow)

## Descrição

Sistema de transcrição de arquivos de áudio (incluindo áudios do WhatsApp) usando SpeechRecognition e FFmpeg para conversão de formatos.

## Funcionalidades

- Transcrição de áudio para texto em português
- Suporte a arquivos de áudio do WhatsApp (.ogg/.opus)
- Conversão automática de formato com FFmpeg
- Output em texto limpo e formatado
- Compatível com múltiplos formatos de áudio

## Stack Tecnológico

| Tecnologia | Descrição |
|---|---|
| Python | Linguagem principal |
| SpeechRecognition | Transcrição de fala |
| FFmpeg | Conversão de formatos de áudio |
| Google Speech API | Motor de reconhecimento |

## Como Usar

1. Instale FFmpeg: [ffmpeg.org](https://ffmpeg.org)
2. Instale dependências: `pip install SpeechRecognition pydub`
3. Execute: `python reconhecer.py caminho/do/audio.ogg`

## Estrutura de Pastas

```
├── reconhecer.py
├── audios/
└── requirements.txt
```

---

> Feito com ❤️ por Rone Bragaglia · ML Engineer & Fundador CobrançaAuto
