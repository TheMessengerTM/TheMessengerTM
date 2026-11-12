<div align="center">

<img src="assets/sekiro-banner.jpg" width="100%" alt="Sekiro" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:120806,50:5C1A10,100:B8321E&height=190&section=header&text=Guilherme%20Hermenegildo&fontSize=42&fontColor=F2D08A&fontAlignY=36&desc=Automa%C3%A7%C3%A3o%20de%20processos%20%C2%B7%20Integra%C3%A7%C3%B5es%20%C2%B7%20RPA&descSize=18&descAlignY=58" alt="Guilherme Hermenegildo" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/guilherme-henrique-da-gra%C3%A7a-hermenegildo-b2b896309)
[![E-mail](https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:guilhermehermenegildo2@gmail.com)

</div>

## Sobre mim

Trabalho com automação na ASTER Segurança. Meu dia a dia é pegar uma tarefa que alguém faz na mão toda semana, como copiar dado de um sistema para outro, montar relatório ou ficar cobrando prazo da equipe, e transformar isso num fluxo que roda sozinho.

A maior parte eu faço em n8n e Power Automate. Quando a ferramenta não dá conta, como nos robôs que baixam os relatórios da FullTrack e da Findme, eu parto para Python.

Quero seguir para backend. Integrando sistemas eu já tive que lidar com evento chegando duplicado, API fora do ar e dado vindo num formato diferente do esperado, e é justamente essa parte que eu mais gosto. O próximo passo é construir os serviços, e não só ligar um no outro.

Os fluxos publicados aqui são os que eu uso no trabalho. Antes de subir, removo credenciais, IDs e dados internos.

## Projetos

**Backend**

| Projeto | O que faz | Stack |
|---|---|---|
| [Gear Sync API](https://github.com/TheMessengerTM/Gear-Sync-API) | Puxa condomínios, unidades e moradores do sistema de controle de acesso GEAR, grava no PostgreSQL sem duplicar e expõe tudo numa API própria. Vem com servidor falso para rodar sem credencial, testes e CI. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |

**n8n**

| Projeto | O que faz | Stack |
|---|---|---|
| [Alert Automation](https://github.com/TheMessengerTM/Alert-Automation) | Manda os alertas de telemetria da Cobli para a central de monitoramento (SIGMA) quase em tempo real. Usa Redis para não repetir alerta e reenvia quando a central não responde. | ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![REST API](https://img.shields.io/badge/REST_API-0A66C2?style=flat-square) |
| [Customer Closing Automation](https://github.com/TheMessengerTM/Customer-Closing-Automation) | O processo de encerramento de contrato de cliente, dividido em 11 fluxos. Começa num e-mail, registra no Microsoft Lists, dá prazo para o Comercial tentar reverter e aciona as equipes por enquete no WhatsApp. | ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat-square&logo=whatsapp&logoColor=white) ![SharePoint](https://img.shields.io/badge/SharePoint-0078D4?style=flat-square&logo=microsoftsharepoint&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |
| [Reminder Automation](https://github.com/TheMessengerTM/Reminder-Automation) | Toda semana manda no grupo da equipe quais manutenções da frota já venceram e quais estão perto de vencer. | ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat-square&logo=whatsapp&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |

**Power Automate**

| Projeto | O que faz | Stack |
|---|---|---|
| [Offboarding Report Automation](https://github.com/TheMessengerTM/Offboarding-Report-Automation) | Relatórios de desligamento, semanais e mensal. Sai uma prévia para a equipe conferir e, três horas depois, a versão corrigida que vai para a diretoria. | ![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white) ![SharePoint](https://img.shields.io/badge/SharePoint-0078D4?style=flat-square&logo=microsoftsharepoint&logoColor=white) ![Outlook](https://img.shields.io/badge/Outlook-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white) |
| [Job Openings Automation](https://github.com/TheMessengerTM/Job-Openings-Automation) | Relatório semanal de quem foi admitido em cada área e um aviso para quem esqueceu de preencher a data de conclusão da vaga. | ![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white) ![SharePoint](https://img.shields.io/badge/SharePoint-0078D4?style=flat-square&logo=microsoftsharepoint&logoColor=white) ![Outlook](https://img.shields.io/badge/Outlook-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white) |
| [Fleet Status Automation](https://github.com/TheMessengerTM/Fleet-Status-Automation) | Avisa os gestores por e-mail quando um veículo da frota muda de base, vai para a manutenção ou é emprestado a outro posto. Só dispara quando o posto muda, não a cada edição na lista. | ![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white) ![SharePoint](https://img.shields.io/badge/SharePoint-0078D4?style=flat-square&logo=microsoftsharepoint&logoColor=white) ![Outlook](https://img.shields.io/badge/Outlook-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white) |

**Automação**

| Projeto | O que faz | Stack |
|---|---|---|
| [FullTrack Report Automation](https://github.com/TheMessengerTM/Fulltrack-Report-Automation) | Robô que entra na FullTrack todo dia, gera os relatórios do dia anterior e salva os CSVs organizados por ano, cliente, mês e tipo. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) |
| [Findme Report Automation](https://github.com/TheMessengerTM/Findme-Report-Automation) | A mesma ideia em outra plataforma: entra na Findme, baixa as planilhas de check-list e comentários de cada viatura de ronda e guarda tudo por ano, mês e posto. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) |

## Ferramentas

<table>
<tr><td><b>Automação</b></td><td>
<img src="assets/icons/n8n.svg" width="48" alt="n8n" title="n8n" />
<img src="assets/icons/powerautomate.svg" width="48" alt="Power Automate" title="Power Automate" />
<img src="assets/icons/playwright.svg" width="48" alt="Playwright" title="Playwright" />
<img src="https://skillicons.dev/icons?i=selenium" width="48" alt="Selenium" title="Selenium" />
<img src="https://skillicons.dev/icons?i=opencv" width="48" alt="OpenCV" title="OpenCV" />
</td></tr>
<tr><td><b>Linguagens</b></td><td>
<img src="https://skillicons.dev/icons?i=py" width="48" alt="Python" title="Python" />
<img src="https://skillicons.dev/icons?i=js" width="48" alt="JavaScript" title="JavaScript" />
<img src="https://skillicons.dev/icons?i=html" width="48" alt="HTML" title="HTML" />
<img src="https://skillicons.dev/icons?i=css" width="48" alt="CSS" title="CSS" />
</td></tr>
<tr><td><b>Integrações e dados</b></td><td>
<img src="assets/icons/restapi.svg" width="48" alt="REST API" title="REST API" />
<img src="assets/icons/microsoft365.svg" width="48" alt="Microsoft 365" title="Microsoft 365" />
<img src="assets/icons/whatsapp.svg" width="48" alt="WhatsApp (WAHA)" title="WhatsApp (WAHA)" />
<img src="https://skillicons.dev/icons?i=redis" width="48" alt="Redis" title="Redis" />
<img src="https://skillicons.dev/icons?i=sqlite" width="48" alt="SQLite" title="SQLite" />
<img src="https://skillicons.dev/icons?i=postgres" width="48" alt="PostgreSQL" title="PostgreSQL" />
</td></tr>
<tr><td><b>Backend</b></td><td>
<img src="https://skillicons.dev/icons?i=fastapi" width="48" alt="FastAPI" title="FastAPI" />
<img src="assets/icons/sqlalchemy.svg" width="48" alt="SQLAlchemy" title="SQLAlchemy" />
<img src="assets/icons/pytest.svg" width="48" alt="pytest" title="pytest" />
<img src="https://skillicons.dev/icons?i=docker" width="48" alt="Docker" title="Docker" />
<img src="https://skillicons.dev/icons?i=githubactions" width="48" alt="GitHub Actions" title="GitHub Actions" />
</td></tr>
<tr><td><b>Outras</b></td><td>
<img src="https://skillicons.dev/icons?i=git" width="48" alt="Git" title="Git" />
<img src="https://skillicons.dev/icons?i=flask" width="48" alt="Flask" title="Flask" />
<img src="assets/icons/jupyter.svg" width="48" alt="Jupyter" title="Jupyter" />
</td></tr>
</table>

## Estudos

Do curso de Python que fiz:

- [Atividades de Python](https://github.com/TheMessengerTM/Araujotrader-Repositorio_Base_GuilhermeHenrique): exercícios de fundamentos, consumo de API, Jupyter, banco de dados, Flask e PyAutoGUI.
- [Avaliação prática do Módulo II](https://github.com/TheMessengerTM/Avaliacao-Pratica-Modulo-ll): uma API de calculadora em Flask e um CRUD em SQLite.
