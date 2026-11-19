<div align="center">

<img src="assets/sekiro-banner.jpg" width="100%" alt="Sekiro" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:120806,50:5C1A10,100:B8321E&height=190&section=header&text=Guilherme%20Hermenegildo&fontSize=42&fontColor=F2D08A&fontAlignY=36&desc=Automa%C3%A7%C3%A3o%20de%20processos%20%C2%B7%20Integra%C3%A7%C3%B5es%20%C2%B7%20IA%20%C2%B7%20RPA&descSize=18&descAlignY=58" alt="Guilherme Hermenegildo" />

<a href="https://www.linkedin.com/in/guilherme-henrique-da-gra%C3%A7a-hermenegildo-b2b896309"><img src="https://skillicons.dev/icons?i=linkedin" width="40" alt="LinkedIn" title="LinkedIn" /></a>
<a href="mailto:guilhermehermenegildo2@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" width="40" alt="E-mail" title="E-mail" /></a>

</div>

## Sobre mim

Trabalho com automação na ASTER Segurança. Meu dia a dia é pegar uma tarefa que alguém faz na mão toda semana, como copiar dado de um sistema para outro, montar relatório ou ficar cobrando prazo da equipe, e transformar isso num fluxo que roda sozinho.

A maior parte eu faço em n8n e Power Automate. Quando a ferramenta não dá conta, como nos robôs que baixam os relatórios da FullTrack e da Findme, eu parto para Python.

Uso IA onde o dado chega como texto livre. Na inclusão de clientes, a IA (OpenAI, com saída estruturada) lê o PDF do formulário preenchido pelo cliente e devolve os campos num JSON com formato fixo. Bolsão, CPF/CNPJ, datas e a checagem de duplicidade ficam em código: deixo para a IA só o que não tem como prever.

Para desenvolver, uso o Claude (Claude Code) como par de programação. Com ele altero os fluxos direto pela API do n8n, escrevo os scripts de apoio, reviso o que vai para produção e preparo os repositórios daqui, inclusive a sanitização antes de publicar.

Quero seguir para backend. Integrando sistemas eu já tive que lidar com evento chegando duplicado, API fora do ar e dado vindo num formato diferente do esperado, e é justamente essa parte que eu mais gosto. O próximo passo é construir os serviços, e não só ligar um no outro.

Os fluxos publicados aqui são os que eu uso no trabalho. Antes de subir, removo credenciais, IDs e dados internos.

## Projetos

**Backend**

| Projeto | O que faz | Stack |
|---|---|---|
| [Gear Sync API](https://github.com/TheMessengerTM/Gear-Sync-API) | Puxa condomínios, unidades e moradores do sistema de controle de acesso GEAR, grava no PostgreSQL sem duplicar e expõe tudo numa API própria. Vem com servidor falso para rodar sem credencial, testes e CI. | <img src="https://skillicons.dev/icons?i=py" width="28" alt="Python" title="Python" /> <img src="https://skillicons.dev/icons?i=fastapi" width="28" alt="FastAPI" title="FastAPI" /> <img src="https://skillicons.dev/icons?i=postgres" width="28" alt="PostgreSQL" title="PostgreSQL" /> <img src="https://skillicons.dev/icons?i=docker" width="28" alt="Docker" title="Docker" /> |

**n8n**

| Projeto | O que faz | Stack |
|---|---|---|
| [Alert Automation](https://github.com/TheMessengerTM/Alert-Automation) | Manda os alertas de telemetria da Cobli para a central de monitoramento (SIGMA) quase em tempo real. Usa Redis para não repetir alerta e reenvia quando a central não responde. | <img src="assets/icons/n8n.svg" width="28" alt="n8n" title="n8n" /> <img src="https://skillicons.dev/icons?i=redis" width="28" alt="Redis" title="Redis" /> <img src="assets/icons/restapi.svg" width="28" alt="REST API" title="REST API" /> |
| [Customer Onboarding Automation](https://github.com/TheMessengerTM/Customer-Onboarding-Automation) | A entrada de um novo cliente no bolsão de segurança, em 11 fluxos. Lê com IA o Termo de Aceite que chega por e-mail, registra no Microsoft Lists e leva Financeiro, Cadastros, Comercial e Operacional até o fim, com enquetes no WhatsApp e uma régua de contato de 30 dias, 60 dias e 1 ano. | <img src="assets/icons/n8n.svg" width="28" alt="n8n" title="n8n" /> <img src="assets/icons/whatsapp.svg" width="28" alt="WhatsApp" title="WhatsApp" /> <img src="assets/icons/sharepoint.svg" width="28" alt="SharePoint" title="SharePoint" /> <img src="assets/icons/outlook.svg" width="28" alt="Outlook" title="Outlook" /> |
| [Customer Closing Automation](https://github.com/TheMessengerTM/Customer-Closing-Automation) | O processo de encerramento de contrato de cliente, dividido em 11 fluxos. Começa num e-mail, registra no Microsoft Lists, dá prazo para o Comercial tentar reverter e aciona as equipes por enquete no WhatsApp. | <img src="assets/icons/n8n.svg" width="28" alt="n8n" title="n8n" /> <img src="assets/icons/whatsapp.svg" width="28" alt="WhatsApp" title="WhatsApp" /> <img src="assets/icons/sharepoint.svg" width="28" alt="SharePoint" title="SharePoint" /> <img src="https://skillicons.dev/icons?i=redis" width="28" alt="Redis" title="Redis" /> |
| [Reminder Automation](https://github.com/TheMessengerTM/Reminder-Automation) | Toda semana manda no grupo da equipe quais manutenções da frota já venceram e quais estão perto de vencer. | <img src="assets/icons/n8n.svg" width="28" alt="n8n" title="n8n" /> <img src="assets/icons/whatsapp.svg" width="28" alt="WhatsApp" title="WhatsApp" /> <img src="https://skillicons.dev/icons?i=js" width="28" alt="JavaScript" title="JavaScript" /> |

**Power Automate**

| Projeto | O que faz | Stack |
|---|---|---|
| [Offboarding Report Automation](https://github.com/TheMessengerTM/Offboarding-Report-Automation) | Relatórios de desligamento, semanais e mensal. Sai uma prévia para a equipe conferir e, três horas depois, a versão corrigida que vai para a diretoria. | <img src="assets/icons/powerautomate.svg" width="28" alt="Power Automate" title="Power Automate" /> <img src="assets/icons/sharepoint.svg" width="28" alt="SharePoint" title="SharePoint" /> <img src="assets/icons/outlook.svg" width="28" alt="Outlook" title="Outlook" /> |
| [Job Openings Automation](https://github.com/TheMessengerTM/Job-Openings-Automation) | Relatório semanal de quem foi admitido em cada área e um aviso para quem esqueceu de preencher a data de conclusão da vaga. | <img src="assets/icons/powerautomate.svg" width="28" alt="Power Automate" title="Power Automate" /> <img src="assets/icons/sharepoint.svg" width="28" alt="SharePoint" title="SharePoint" /> <img src="assets/icons/outlook.svg" width="28" alt="Outlook" title="Outlook" /> |
| [Fleet Status Automation](https://github.com/TheMessengerTM/Fleet-Status-Automation) | Avisa os gestores por e-mail quando um veículo da frota muda de base, vai para a manutenção ou é emprestado a outro posto. Só dispara quando o posto muda, não a cada edição na lista. | <img src="assets/icons/powerautomate.svg" width="28" alt="Power Automate" title="Power Automate" /> <img src="assets/icons/sharepoint.svg" width="28" alt="SharePoint" title="SharePoint" /> <img src="assets/icons/outlook.svg" width="28" alt="Outlook" title="Outlook" /> |

**Automação**

| Projeto | O que faz | Stack |
|---|---|---|
| [FullTrack Report Automation](https://github.com/TheMessengerTM/Fulltrack-Report-Automation) | Robô que entra na FullTrack todo dia, gera os relatórios do dia anterior e salva os CSVs organizados por ano, cliente, mês e tipo. | <img src="https://skillicons.dev/icons?i=py" width="28" alt="Python" title="Python" /> <img src="assets/icons/playwright.svg" width="28" alt="Playwright" title="Playwright" /> |
| [Findme Report Automation](https://github.com/TheMessengerTM/Findme-Report-Automation) | A mesma ideia em outra plataforma: entra na Findme, baixa as planilhas de check-list e comentários de cada viatura de ronda e guarda tudo por ano, mês e posto. | <img src="https://skillicons.dev/icons?i=py" width="28" alt="Python" title="Python" /> <img src="https://skillicons.dev/icons?i=selenium" width="28" alt="Selenium" title="Selenium" /> <img src="https://skillicons.dev/icons?i=opencv" width="28" alt="OpenCV" title="OpenCV" /> |

## Ferramentas

<table>
<tr><td><b>Automação</b></td><td>
<img src="assets/icons/n8n.svg" width="48" alt="n8n" title="n8n" />
<img src="assets/icons/powerautomate.svg" width="48" alt="Power Automate" title="Power Automate" />
<img src="assets/icons/playwright.svg" width="48" alt="Playwright" title="Playwright" />
<img src="https://skillicons.dev/icons?i=selenium" width="48" alt="Selenium" title="Selenium" />
<img src="https://skillicons.dev/icons?i=opencv" width="48" alt="OpenCV" title="OpenCV" />
</td></tr>
<tr><td><b>IA</b></td><td>
<img src="assets/icons/openai.svg" width="48" alt="OpenAI" title="OpenAI" />
<img src="assets/icons/claude.svg" width="48" alt="Claude" title="Claude (Claude Code)" /></td></tr>
<tr><td><b>Linguagens</b></td><td>
<img src="https://skillicons.dev/icons?i=py" width="48" alt="Python" title="Python" />
<img src="https://skillicons.dev/icons?i=js" width="48" alt="JavaScript" title="JavaScript" />
<img src="https://skillicons.dev/icons?i=ts" width="48" alt="TypeScript" title="TypeScript" />
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
<img src="https://skillicons.dev/icons?i=mongodb" width="48" alt="MongoDB" title="MongoDB" />
</td></tr>
<tr><td><b>Backend</b></td><td>
<img src="https://skillicons.dev/icons?i=fastapi" width="48" alt="FastAPI" title="FastAPI" />
<img src="https://skillicons.dev/icons?i=nestjs" width="48" alt="NestJS" title="NestJS" />
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

Da faculdade:

- [Controle Financeiro API](https://github.com/TheMessengerTM/Controle-Financeiro-API): API em NestJS e MongoDB para registrar receitas e despesas e devolver o saldo, o total de despesas e quanto foi gasto por impulso. Atividade de Web Mobile ligada a um projeto extensionista (ODS 1 e ODS 12).
