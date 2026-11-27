<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:14b8a6,100:38bdf8&height=200&section=header&text=Antonio%20Gabriel&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Backend%20%C2%B7%20Automa%C3%A7%C3%B5es%20%C2%B7%20Criador%20do%20VitriMini&descAlignY=55&descSize=17" alt="Antonio Gabriel — Backend · Automações · Criador do VitriMini" />

Desenvolvedor full-stack com foco em backend. Construo as automações fiscais que rodam em produção na **Contas Contabilidade** e produtos próprios — o mais novo é o **[VitriMini](https://vitrimini.com.br)**.

[![VitriMini](https://img.shields.io/badge/VitriMini-vitrimini.com.br-e11d48?style=for-the-badge)](https://vitrimini.com.br)
[![Portfólio](https://img.shields.io/badge/Portfólio-antoniogabriel.vercel.app-14b8a6?style=for-the-badge&logo=vercel&logoColor=white)](https://antoniogabriel.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Antonio%20Gabriel-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://br.linkedin.com/in/antoniofalcaonascimento)
[![E-mail](https://img.shields.io/badge/E--mail-Contato-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nascimentogabriel.2004@gmail.com)

</div>

---

<div align="center">
  <a href="https://vitrimini.com.br">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./assets/vitrimini-logo-escuro.png" />
      <img src="./assets/vitrimini-logo.png" alt="VitriMini" height="56" />
    </picture>
  </a>

![Em produção](https://img.shields.io/badge/status-em%20produção-16a34a?style=flat-square)

**Vitrine digital e link na bio para quem vende por encomenda.**<br/>
O cliente escolhe data e turno, paga o sinal no Pix e o pedido chega pronto no WhatsApp — sem comissão sobre a venda.

<a href="https://vitrimini.com.br"><img src="./assets/vitrimini-capa.png" alt="VitriMini — vitrine digital e link na bio em minutos" width="85%" /></a>

</div>

- **Para quem vende:** catálogo montado em minutos, agenda por data e turno e painel de pedidos ao vivo.
- **Para quem compra:** carrinho somado na hora, sinal pelo Mercado Pago ou pela chave Pix e resumo pronto no WhatsApp.
- **Stack:** React 19, Vite, Tailwind v4 · Node.js, Express, Prisma, PostgreSQL · Mercado Pago.

<!-- VÍDEOS: no editor do GitHub, arraste cliente-demo.mp4 e painel-demo.mp4 no lugar das duas linhas
     COLE_AQUI e apague as linhas de comentário (esta e a que fecha o bloco).
<details>
<summary><b>▶️ Ver o VitriMini funcionando</b> — a vitrine do cliente e o painel de pedidos</summary>

COLE_AQUI_O_VIDEO_DA_VITRINE

COLE_AQUI_O_VIDEO_DO_PAINEL

</details>
-->

<p align="center"><a href="https://vitrimini.com.br"><b>Acessar o VitriMini</b></a> · <a href="https://github.com/copperlamb78/vitrimini">Ver o código</a></p>

---

## 🏭 Automação fiscal em produção

Na **Contas Contabilidade**, construo e mantenho a plataforma em **NestJS** que orquestra **mais de 20 automações** do fiscal e contábil — SPED, PGDAS, DCTFWeb, NF-e e NFS-e, certidões e caixa postal eletrônica. Cada empresa vira uma mensagem no **RabbitMQ**, e um painel próprio mostra o que rodou, o que falhou e por quê.

<div align="center">

| ⚙️ Automações | 🔁 Ciclos | 🏢 Empresas processadas | ✅ Sucesso por empresa |
| :---: | :---: | :---: | :---: |
| **20+** | **141**, todos concluídos | **+70 mil** | **97%** |

<sub>Painel de produção, 27/06 a 27/11/2026. Pendência de cadastro (certificado ausente, cadastro incompleto) fica fora da taxa: não é falha do código.</sub>

</div>

**Caso em destaque — caixa postal eletrônica (DTE).** Varredura semanal de ~620 empresas, em produção desde março de 2026:

<div align="center">

| | Antes | Hoje |
| :--- | :---: | :---: |
| ⏱️ Tempo por rodada | 50 a 80 h | **~4h30** |
| 🏢 Tempo por empresa | ~6 min | **~26 s** |
| 💰 Custo de IA por rodada | — | **R$ 0,35** |

</div>

> Cerca de 60 horas devolvidas ao time por semana, por 35 centavos de IA. A virada foi trocar o OCR do CAPTCHA por visão computacional, o que deixou a rodada inteira desassistida.

- 📨 **Orientada a eventos:** uma mensagem por empresa e callback em vez de *polling* — uma empresa que falha não derruba as outras.
- 🔭 **Nada falha em silêncio:** painel com status, histórico, custos e alerta de agendamento perdido. É de lá que saem os números acima.
- 🧠 **IA onde resolve:** Gemini para CAPTCHA e leitura de documentos, como peça do sistema e não como enfeite.

---

## 📌 Outros projetos

| Projeto | O que é | Stack |
| :--- | :--- | :--- |
| 📅 **[SinalizeGO](https://github.com/copperlamb78/api-sinalizego)**<br/><sub>🚧 em desenvolvimento</sub> | Agendamento com sinal via Pix: o valor fica em custódia e é liquidado com split ao fim do atendimento. | NestJS, Prisma, PostgreSQL, Asaas |
| 🎙️ **[Assistente de Reuniões IA](https://github.com/copperlamb78/backend_conversor)** | Transcreve o áudio da reunião e devolve um resumo estruturado. Backend HTTP + app desktop. | Express, Whisper, Gemini, Electron |
| 🏋️ **[AriseFit](https://github.com/copperlamb78/AriseFit)** | App de treino calistênico gamificado: missão diária, níveis, ranks e sequência. | React Native, Expo, TypeScript, Zustand |

<sub>🔒 As automações da empresa vivem em repositórios privados.</sub>

---

## 🛠️ Stack

<div align="center">

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
<br/>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

</div>

<details>
<summary><b>🧰 Ver tudo que já usei em projeto real</b></summary>

<div align="center">

### 💻 Frontend
![React](https://img.shields.io/badge/React-111827?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-111827?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-111827?style=for-the-badge&logo=typescript&logoColor=3178C6)
![JavaScript](https://img.shields.io/badge/JavaScript-111827?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-111827?style=for-the-badge&logo=tailwind-css&logoColor=38B2AC)
![Chakra UI](https://img.shields.io/badge/Chakra_UI-111827?style=for-the-badge&logo=chakraui&logoColor=319795)
![Styled Components](https://img.shields.io/badge/Styled_Components-111827?style=for-the-badge&logo=styled-components&logoColor=DB7093)
![Vite](https://img.shields.io/badge/Vite-111827?style=for-the-badge&logo=vite&logoColor=646CFF)
![Electron](https://img.shields.io/badge/Electron-111827?style=for-the-badge&logo=electron&logoColor=47848F)
![React Native](https://img.shields.io/badge/React_Native-111827?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-111827?style=for-the-badge&logo=expo&logoColor=white)

### ⚙️ Backend & APIs
![Node.js](https://img.shields.io/badge/Node.js-111827?style=for-the-badge&logo=node.js&logoColor=339933)
![NestJS](https://img.shields.io/badge/NestJS-111827?style=for-the-badge&logo=nestjs&logoColor=E0234E)
![Express](https://img.shields.io/badge/Express-111827?style=for-the-badge&logo=express&logoColor=white)
![Python](https://img.shields.io/badge/Python-111827?style=for-the-badge&logo=python&logoColor=3776AB)
![FastAPI](https://img.shields.io/badge/FastAPI-111827?style=for-the-badge&logo=fastapi&logoColor=009688)
![Prisma](https://img.shields.io/badge/Prisma-111827?style=for-the-badge&logo=prisma&logoColor=2D3748)
![Swagger](https://img.shields.io/badge/Swagger-111827?style=for-the-badge&logo=swagger&logoColor=85EA2D)
![JWT](https://img.shields.io/badge/JWT-111827?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-111827?style=for-the-badge&logo=pm2&logoColor=2B037A)

### 🗄️ Banco de Dados
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-111827?style=for-the-badge&logo=postgresql&logoColor=4169E1)
![MongoDB](https://img.shields.io/badge/MongoDB-111827?style=for-the-badge&logo=mongodb&logoColor=47A248)
![Supabase](https://img.shields.io/badge/Supabase-111827?style=for-the-badge&logo=supabase&logoColor=3FCF8E)
![Redis](https://img.shields.io/badge/Redis-111827?style=for-the-badge&logo=redis&logoColor=DC382D)
![SQLite](https://img.shields.io/badge/SQLite-111827?style=for-the-badge&logo=sqlite&logoColor=003B57)
![DuckDB](https://img.shields.io/badge/DuckDB-111827?style=for-the-badge&logo=duckdb&logoColor=FFF000)

### 📨 Mensageria, Infra & Observabilidade
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-111827?style=for-the-badge&logo=rabbitmq&logoColor=FF6600)
![Sentry](https://img.shields.io/badge/Sentry-111827?style=for-the-badge&logo=sentry&logoColor=362D59)
![Firebase](https://img.shields.io/badge/Firebase-111827?style=for-the-badge&logo=firebase&logoColor=FFCA28)
![Vercel](https://img.shields.io/badge/Vercel-111827?style=for-the-badge&logo=vercel&logoColor=white)

### 🧠 IA Aplicada
![Google Gemini](https://img.shields.io/badge/Gemini-111827?style=for-the-badge&logo=googlegemini&logoColor=8E75B2)
![Whisper](https://img.shields.io/badge/Whisper-111827?style=for-the-badge&logo=openai&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-111827?style=for-the-badge&logo=opencv&logoColor=5C3EE8)
![Tesseract OCR](https://img.shields.io/badge/Tesseract_OCR-111827?style=for-the-badge)

### 🤖 Automação, Scraping & Ferramentas
![Selenium](https://img.shields.io/badge/Selenium-111827?style=for-the-badge&logo=selenium&logoColor=43B02A)
![Playwright](https://img.shields.io/badge/Playwright-111827?style=for-the-badge&logo=playwright&logoColor=2EAD33)
![Puppeteer](https://img.shields.io/badge/Puppeteer-111827?style=for-the-badge&logo=puppeteer&logoColor=40B5A4)
![Git](https://img.shields.io/badge/Git-111827?style=for-the-badge&logo=git&logoColor=F05032)
![GitHub](https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-111827?style=for-the-badge&logo=figma&logoColor=F24E1E)

</div>

</details>

---

## 📊 No GitHub

<div align="center">
  <img src="./github-metrics.svg" alt="Métricas do GitHub" width="100%" />
</div>

---

<div align="center">

Aberto a oportunidades e freelas de **backend, automação e SaaS** — me chama no [LinkedIn](https://br.linkedin.com/in/antoniofalcaonascimento) ou por [e-mail](mailto:nascimentogabriel.2004@gmail.com).

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/copperlamb78/copperlamb78/output/github-contribution-grid-snake-dark.svg?v=3" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/copperlamb78/copperlamb78/output/github-contribution-grid-snake.svg?v=3" />
  <img src="https://raw.githubusercontent.com/copperlamb78/copperlamb78/output/github-contribution-grid-snake-dark.svg?v=3" alt="Cobrinha comendo o gráfico de contribuições" />
</picture>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:38bdf8,50:14b8a6,100:0f172a&height=120&section=footer" alt="" />

</div>
