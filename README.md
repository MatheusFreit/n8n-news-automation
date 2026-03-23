# 🚀 n8n News Automation

Automação de coleta e envio de notícias usando n8n.

## 📌 Sobre

Fluxo automatizado que roda **2x por dia (08:00 e 20:00)** coletando notícias, resumindo com IA e enviando para o Discord.

---

## ⚙️ Funcionalidades

### 📰 Notícias
- RSS:
  - Olhar Digital
  - CanalTech
  - CNN Brasil
- Limite de 5 notícias por fonte
- Cache com Redis (TTL de 1 dia)
- Resumo com IA

### 📺 YouTube
- Monitoramento de canais
- Notificação automática

### 💰 Cotação
- USD e EUR via Brasil API

### 🧹 Limpeza
- Remove mensagens antigas automaticamente

---

## 🧠 Tecnologias

- n8n
- Redis
- OpenRouter (IA)
- Discord Webhook
- RSS

---

## ⏱️ Execução

- 08:00
- 20:00

---

## 📥 Como usar

1. Importe o arquivo:
