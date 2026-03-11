# EverIA — WhatsApp QR Site

Site estático para exibir o QR Code de conexão do WhatsApp.

## Como funciona

1. O script `push-qr.mjs` gera o QR via OpenClaw e faz push do `qr.png` + `meta.json` para este repo
2. A Vercel detecta o push e faz deploy automático (~10s)
3. O usuário acessa a URL e escaneia o QR no WhatsApp

## Deploy

Este site é hospedado na Vercel via integração GitHub.
O deploy é automático a cada push na branch `main`.
