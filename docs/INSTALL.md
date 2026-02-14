# 🔧 Установка и настройка

## Требования

- n8n (self-hosted или cloud)
- HeyGen API ключ
- Аккаунт HeyGen с API кредитами

## Шаг 1: Установка n8n

### Docker
```bash
docker run -it --rm \
  --name n8n \
  -p 5678:5678 \
  -v ~/.n8n:/home/node/.n8n \
  n8nio/n8n
