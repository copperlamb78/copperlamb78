<!-- Banner Topo -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:14b8a6,100:38bdf8&height=220&section=header&text=Antonio%20Gabriel&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Full-Stack%20Developer%20%7C%20Backend%20%7C%20Automações%20%7C%20SaaS&descAlignY=55&descSize=17" alt="Header" />
</div>

<div align="center">

# 👋 Olá, eu sou o Antonio Gabriel

### **Desenvolvedor Full-Stack focado em Backend, Automações e Produtos Digitais**

Portfólio, contatos e redes sociais de forma rápida:

[![Portfolio](https://img.shields.io/badge/Portfólio-antoniogabriel.vercel.app-14b8a6?style=for-the-badge&logo=vercel&logoColor=white)](https://antoniogabriel.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Antonio%20Gabriel-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://br.linkedin.com/in/antoniofalcaonascimento)
[![Email](https://img.shields.io/badge/E--mail-Contato-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nascimentogabriel.2004@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-copperlamb78-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/copperlamb78)

---

</div>

## 🚀 Sobre mim

Sou um desenvolvedor em evolução constante, movido pelo desafio de criar aplicações úteis, organizadas e com impacto real no ecossistema de empresas e usuários.

* 💼 **Atuação Atual:** Faço parte do time da **Contas Contabilidade** (uma das maiores empresas do setor na Bahia/Nordeste), onde desenvolvo e mantenho **automações rodando em produção** que substituem processos manuais e repetitivos do time fiscal e contábil — de crawlers em portais governamentais a integrações, agendadores e ferramentas internas.
* 🧠 **Filosofia de Código:** Gosto de construir projetos do zero para dominar as regras de negócio e a arquitetura subjacente. Uso IA de forma estratégica para produtividade, mas prezo pelo aprendizado sólido e manual das bases técnicas.

> 💡 *Para mim, tecnologia precisa resolver problemas reais e gerar valor, não apenas parecer bonita no código.*

---

## 🏭 Automação em Produção

Meu principal trabalho hoje é uma **plataforma em NestJS que orquestra mais de 10 automações** do dia a dia contábil-fiscal. Não são scripts isolados: é um sistema único, com fila de mensagens, agendamento, observabilidade e tratamento de falha — porque automação que quebra em silêncio é pior do que processo manual.

| Frente | O que resolve | Stack principal |
| :--- | :--- | :--- |
| 📄 **Obrigações fiscais federais** | Apuração e entrega recorrente de obrigações (SPED, PGDAS, DCTFWeb): geração, validação e transmissão automatizada. | NestJS, TypeScript, Playwright |
| 🧾 **Notas fiscais (NF-e / NFS-e)** | Consulta, download e confronto de notas em portais estaduais e municipais, com conciliação automática. | Python, Selenium, Node.js, HTTP/2 |
| 🏛️ **Tributos municipais** | Emissão e download de guias, consulta cadastral e geração de PDF fiel ao layout original. | Puppeteer, FastAPI, WeasyPrint |
| 📬 **Caixa postal eletrônica (DTE)** | Varredura periódica de comunicados e alertas, com leitura de imagem por visão computacional. | Playwright, Google Vision, Gemini |
| 🔐 **Certificados digitais** | Leitura de arquivos `.pfx`, extração de titular e vencimento, controle de validade e assinatura de documentos. | Node.js, node-forge |
| 📊 **Relatórios e conciliação** | Consolidação em Excel, geração de PDF assinado e disparo automático por e-mail. | ExcelJS, pdfmake, Nodemailer |
| 👥 **Ferramentas internas** | Apps desktop e web para o time operar as automações sem depender de linha de comando. | Next.js, React, Electron, Firebase |

### 📈 Números de produção

Extraídos do registro de execução da própria plataforma *(dados até 04/08/2026)*:

<div align="center">

| 🔁 Execuções | ✅ Execuções OK | 🏢 Processamentos | ✅ Registros OK | ⚙️ Automações |
| :---: | :---: | :---: | :---: | :---: |
| **99** | **99%** | **+12.000** | **94%** | **15** |

</div>

*Duas taxas porque medem coisas diferentes: **99%** é a orquestração concluindo o ciclo; **94%** é o resultado empresa a empresa — onde entram cadastro desatualizado na origem, procuração vencida, permissão negada e portal fora do ar. São causas externas ao código, e rastreá-las separadamente foi uma decisão de projeto.*

* 🎯 **13 ciclos concluídos, nenhum pendente** — cadências diária, semanal, mensal e trimestral rodando em paralelo.
* 🔧 **1 única falha de execução em 99** — causa identificada e corrigida no mesmo ciclo.

---

**Caso em destaque** — a automação de varredura da **caixa postal eletrônica (DTE)**, em produção semanal **desde março de 2026**, percorrendo centenas de empresas por rodada:

<div align="center">
  
| Métrica | Antes | Depois |
| :--- | :--- | :--- |
| ⏱️ Tempo total de execução | 50 a 80 horas | **5 a 7 horas** |
| 🏢 Tempo por empresa | ~6 minutos | **~34 segundos** |
| 💰 Custo de IA por execução | — | **R$ 0,33** |

</div>
* ⚡ **~10x mais rápido** — cerca de **90% de redução** no tempo total.
* ⏳ **~60 horas devolvidas ao time a cada execução** — o equivalente a **1,5 semana** de trabalho de uma pessoa.
* 🪙 **R$ 0,0005 por empresa processada** — cada **R$ 1,00** em IA cobre aproximadamente **1.900 empresas**.
* 🧠 A virada veio de substituir a leitura via OCR do CAPTCHA por **visão computacional**, tornando a execução inteira desassistida.
* 🎯 **100% das rodadas concluídas.** As poucas empresas não processadas por semana são cadastro desatualizado na planilha de origem — atualizado o cadastro, processa normalmente.

> 60 horas de trabalho humano trocadas por 33 centavos de processamento.

**Outros resultados em produção:**

* 📊 **Relatórios tributários** — assumi uma automação existente e a reescrevi sobre **RabbitMQ com processamento idempotente**. Resultado: de **95% para 100% de sucesso** entre dois ciclos consecutivos, eliminando 104 falhas recorrentes.
* 💰 **Controle de caixa** — construída do zero, **~84 empresas por minuto** e **nenhuma falha registrada** desde a entrada em produção.
* 🔄 **Sincronização diária de cadastro** — **56 execuções consecutivas sem uma única falha**, ~2 min cada.

**O que aprendi construindo isso:**

* 📨 **Arquitetura orientada a eventos** — migração de *polling* para *push* com **RabbitMQ**, ganhando throughput e derrubando latência de processamento.
* 🛡️ **Resiliência é requisito, não bônus** — retry com backoff, *kill-switch*, fallback de seletores e reprocessamento idempotente. Portal do governo cai, muda layout e responde estranho: o código precisa sobreviver a isso.
* 🔭 **Falha silenciosa é o pior tipo de falha** — com muitas automações rodando, diagnosticar dependia de vasculhar log do PM2 no servidor, e erro que não avisa passa despercebido por dias. Construí um **painel administrativo** que centraliza status, histórico e métricas de cada automação. Foi o que transformou "acho que rodou" em número — inclusive todos os desta seção, que só existem porque o painel existe.
* 🧯 **Observabilidade além do painel** — **Sentry** para captura de exceção e logs estruturados, para conseguir responder *"por que essa automação não rodou ontem?"* sem abrir o servidor.
* 🧠 **IA aplicada com propósito** — **Gemini** e **Google Cloud Vision** para leitura de documentos e imagens; **Whisper** para transcrição de áudio. IA como componente do sistema, não como enfeite.
* ⏱️ **Agendamento e orquestração** — jobs recorrentes com `@nestjs/schedule` e `node-cron`, processos de longa duração sob **PM2**.

---

## 🛠️ Stack

<div align="center">

### ⭐ Especialidades

*As tecnologias em que eu entrego com profundidade, não só familiaridade:*

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
<summary><b>🧰 Ver arsenal completo</b> — tudo que já usei em projeto real</summary>

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
![SQL](https://img.shields.io/badge/SQL-111827?style=for-the-badge&logo=sqlite&logoColor=003B57)

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

## 🎯 Foco Atual & Desenvolvimento

* 🚀 **Em Destaque — SinalizeGO:** API de agendamento para profissionais autônomos e pequenos negócios (barbearias, estúdios, salões), construída em **NestJS + Prisma + PostgreSQL**. O diferencial é o modelo financeiro: sem mensalidade para o profissional — a plataforma se sustenta por uma taxa progressiva sobre o sinal, com **split de pagamento via Pix** integrado ao gateway.
* 🏗️ **Arquitetura Orientada a Eventos:** Desenho de sistemas que se comunicam por **mensageria (RabbitMQ)** em vez de acoplamento direto, com foco em throughput, idempotência e recuperação de falha.
* 🛠️ **Backend Sólido:** Construção de APIs REST robustas e estruturadas com **NestJS**, **Node.js** e **TypeScript**, sempre documentadas com **Swagger**.
* 🔐 **Segurança em APIs:** Aprofundamento em autorização multi-tenant, proteção de fluxos que envolvem dinheiro e o princípio de nunca confiar em valor vindo do cliente.
* 📊 **Persistência:** Modelagem de dados e otimização de consultas com **PostgreSQL**, **Prisma** e **MongoDB**.
* 🤖 **Web Scraping:** Crawlers resilientes com **Python**, **Selenium**, **Playwright** e **Puppeteer**, incluindo OCR e visão computacional quando o portal não coopera.

---

## 📌 Projetos em Destaque

| Projeto | Principais Tecnologias | Descrição |
| :--- | :--- | :--- |
| 📅 **[SinalizeGO API](https://github.com/copperlamb78/api-sinalizego)** | NestJS, Prisma, PostgreSQL, Pix | Plataforma de agendamento com sinal via Pix e split automático de pagamento. Projeto autoral em evolução. |
| 🎙️ **[Assistente de Reuniões IA](https://github.com/copperlamb78/backend_conversor)** | Express, Whisper, Gemini, Electron | Transcreve o áudio de uma reunião e devolve resumo estruturado. Backend HTTP + app desktop. |
| 🧰 **[Toolkit](https://github.com/copperlamb78/toolkit)** | NestJS, TypeScript, JS | API robusta focada em arquitetura escalável e organização rígida de rotas. |
| 💼 **[BusinessCorp](https://github.com/copperlamb78/businessCorp_Portfolio)** | TypeScript, Vite | Portfólio institucional sob medida para TCC de Administração do SENAI. |
| 💳 **Meu Caixa** | Stack Full-Stack | SaaS de controle financeiro pessoal e empresarial, com foco em experiência de uso limpa e direta. |
| 🌐 **[Portfólio Pessoal](https://github.com/copperlamb78/portifolio_gabriel)** | Vite, TypeScript | Minha vitrine digital para consolidar projetos, artigos e histórico profissional. |
| ♻️ **[Electronic Recycling](https://github.com/copperlamb78/Eletronic_Recycling)** | TypeScript, Geolocalização | App que mapeia pontos de descarte eletrônico próximos com base no IP do usuário. |
| 🌱 **[ECO](https://github.com/copperlamb78/ECO_Frontend)** | HTML, Python | Projeto acadêmico colaborativo. Entrei em base de código já existente para **diagnosticar e corrigir bugs** que travavam o projeto — depurar código que não é seu é uma habilidade à parte. |
| 🛡️ **[Gerador de CPF](https://github.com/copperlamb78/validador-e-gerador-de-cpf)** | Python | Script inteligente para validação, geração e exportação de CPFs válidos. |
| 📝 **[Task List](https://github.com/copperlamb78/Task_list)** | Python | Utilitário leve e objetivo voltado para a gestão de tarefas cotidianas. |

> 🔒 As automações fiscais e ferramentas internas citadas na seção **Automação em Produção** vivem em repositórios privados da empresa e, por isso, não estão listadas aqui.

---

## 💼 Serviços Freelancer & Soluções Comerciais

Estou expandindo minha atuação como desenvolvedor independente. Desenvolvo soluções sob medida com foco em performance e prazos reais:

* 🌐 **Aplicações Web:** Landing Pages de alta conversão, Sites Institucionais e Portfólios de alto padrão.
* ⚙️ **Sistemas & Integrações:** Criação de APIs REST, Dashboards dinâmicos, Ferramentas internas e Conexão de Bancos de Dados.
* 🤖 **Inteligência Operacional:** Automação de processos manuais na web, web scraping e extração estruturada de dados.
* 💳 **Pagamentos & SaaS:** Integração de gateways, cobrança recorrente, split de pagamento e modelagem de produto digital.

---

## 📊 Estatísticas do GitHub

<div align="center">

<img src="./github-metrics.svg" alt="GitHub Metrics" width="100%" />

</div>

---

## 🧩 Um Pouco da Minha Sintaxe

```ts
const antonioGabriel = {
  role: "Full-Stack Developer",
  focus: ["Backend", "APIs", "Automações", "Web Scraping", "SaaS", "Freelance"],
  mainStack: ["Node.js", "NestJS", "TypeScript", "Prisma", "Python", "FastAPI", "React", "Next.js"],
  automation: ["Playwright", "Puppeteer", "Selenium", "RabbitMQ", "Gemini"],
  currentlyLearning: [
    "Arquitetura orientada a eventos",
    "Mensageria e idempotência",
    "Segurança em APIs de pagamento",
    "Testes automatizados",
  ],
  mindset: "Construir, testar, errar, melhorar e repetir.",
};
```

---

## 🤝 Vamos conversar?

Estou aberto a **oportunidades**, **projetos freelance** e **trocas técnicas** — principalmente se envolver backend, automação ou produto digital do zero.

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfólio-antoniogabriel.vercel.app-14b8a6?style=for-the-badge&logo=vercel&logoColor=white)](https://antoniogabriel.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vamos%20conectar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://br.linkedin.com/in/antoniofalcaonascimento)
[![Email](https://img.shields.io/badge/E--mail-Me%20chama-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nascimentogabriel.2004@gmail.com)

</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/rodrigofelipe3/rodrigofelipe3/output/github-contribution-grid-snake-dark.svg" alt="Cobrinha" />
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:38bdf8,50:14b8a6,100:0f172a&height=120&section=footer" alt="Footer" />
</div>
