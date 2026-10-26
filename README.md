# Olá, eu sou o Guilherme Hermenegildo 👋

Desenvolvo automações e integrações entre sistemas, principalmente com **n8n**, para tirar trabalho manual da operação: alertas que chegam sozinhos na central, lembretes que avisam a equipe antes de algo vencer e dados que passam de uma plataforma para outra sem ninguém copiar e colar.

Este perfil reúne essas automações. Cada repositório é um projeto, com o fluxo pronto para importar, a explicação do problema que ele resolve e as decisões de projeto.

## 🧰 Tecnologias

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp_(WAHA)-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-0A66C2?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## 🚀 Automações

### [🚨 Alert Automation](https://github.com/TheMessengerTM/Alert-Automation)

Leva os alertas de telemetria veicular da **Cobli** (como a saída de um veículo do bolsão) para a central de monitoramento **SIGMA (Segware)** quase em tempo real, sem duplicar eventos.

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-0A66C2?style=flat-square)
![Cobli](https://img.shields.io/badge/Cobli-telemetria-555555?style=flat-square)
![SIGMA](https://img.shields.io/badge/SIGMA-Segware-555555?style=flat-square)

### [🔧 Reminder Automation](https://github.com/TheMessengerTM/Reminder-Automation)

Toda semana, confere os lembretes de manutenção da frota na **Cobli** e envia ao grupo de **WhatsApp** da equipe um resumo das manutenções vencidas e das que estão perto de vencer.

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![WhatsApp](https://img.shields.io/badge/WhatsApp_(WAHA)-25D366?style=flat-square&logo=whatsapp&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-0A66C2?style=flat-square)
![Cobli](https://img.shields.io/badge/Cobli-telemetria-555555?style=flat-square)

## 🔒 Sobre os fluxos publicados

Antes de publicar, todo fluxo passa por um script em **Python** que remove chaves de API, credenciais, IDs de conta, endereços internos e dados pessoais. Os valores sensíveis são trocados por marcadores (`<<PREENCHER>>`), e o fluxo pode ser importado e configurado em qualquer instância do n8n.
