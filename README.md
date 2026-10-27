# Olá, eu sou o Guilherme Hermenegildo 👋

Desenvolvo automações e integrações entre sistemas para tirar trabalho manual da operação: alertas que chegam sozinhos na central, lembretes que avisam a equipe antes de algo vencer, robôs que baixam e organizam relatórios e dados que passam de uma plataforma para outra sem ninguém copiar e colar.

Uso principalmente **n8n** e **Power Automate** para orquestrar integrações e **Python** para robôs (RPA) e scripts. Cada repositório de automação é um projeto, com o problema que ele resolve, como funciona e como usar.

## 🧰 Tecnologias

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp_(WAHA)-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft_365-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
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
![Cobli](https://img.shields.io/badge/Cobli-manutenção_de_frota-555555?style=flat-square)

### [📋 Customer Closing Automation](https://github.com/TheMessengerTM/Customer-Closing-Automation)

Conduz o **encerramento de contrato** de clientes em 11 fluxos: recebe o pedido por **e-mail**, registra no **Microsoft Lists**, dá ao Comercial um prazo para recuperar o cliente e aciona o Operacional e o time de Sistemas por **enquetes no WhatsApp**, com controle de prazos e lembretes automáticos.

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![WhatsApp](https://img.shields.io/badge/WhatsApp_(WAHA)-25D366?style=flat-square&logo=whatsapp&logoColor=white)
![Microsoft Lists](https://img.shields.io/badge/Microsoft_Lists-SharePoint-0078D4?style=flat-square&logo=microsoftsharepoint&logoColor=white)
![Outlook](https://img.shields.io/badge/Outlook-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### [📊 Offboarding Report Automation](https://github.com/TheMessengerTM/Offboarding-Report-Automation)

Gera os relatórios de desligamento do RH e da Psicologia a partir das entrevistas registradas no **SharePoint** e os envia por **e-mail**: primeiro uma prévia para a equipe conferir e completar a lista, depois a versão final, atualizada, que segue para a diretoria.

![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white)
![Microsoft Lists](https://img.shields.io/badge/Microsoft_Lists-SharePoint-0078D4?style=flat-square&logo=microsoftsharepoint&logoColor=white)
![Outlook](https://img.shields.io/badge/Outlook-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)

### [🤖 FullTrack Report Automation](https://github.com/TheMessengerTM/Fulltrack-Report-Automation)

Robô (RPA) que entra na plataforma **FullTrack**, gera os relatórios do dia anterior (permanência em ponto e trajeto percorrido), exporta em CSV e organiza os arquivos em pastas por ano, cliente/posto, mês e tipo de relatório.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![RPA](https://img.shields.io/badge/RPA-automação_web-6E40C9?style=flat-square)
![CSV](https://img.shields.io/badge/CSV-relatórios-217346?style=flat-square)

## 📚 Estudos

### [🐍 Repositório de atividades de Python](https://github.com/TheMessengerTM/Araujotrader-Repositorio_Base_GuilhermeHenrique)

Atividades do curso de Python: fundamentos (condicionais, listas, laços, tratamento de erros), consumo de APIs, manipulação de dados com Jupyter, banco de dados, desenvolvimento web e automação com PyAutoGUI.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)

### [📝 Avaliação prática — Módulo II](https://github.com/TheMessengerTM/Avaliacao-Pratica-Modulo-ll)

Avaliação do curso em duas partes: uma API REST de calculadora com **Flask** (rotas com parâmetros na URL e resposta em JSON) e um CRUD completo em **SQLite**.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-0A66C2?style=flat-square)

## 🔒 Sobre os fluxos publicados

Antes de publicar, todo fluxo (n8n ou Power Automate) passa por um script em **Python** que remove chaves de API, credenciais, IDs de conta, endereços internos e dados pessoais. Os valores sensíveis são trocados por marcadores (`<<PREENCHER>>`), e o fluxo pode ser importado e configurado em outro ambiente.
