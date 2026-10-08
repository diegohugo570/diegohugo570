<!-- Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Diego%20Hugo&fontSize=58&fontColor=ffffff&desc=AI%20Engineer%20%E2%80%A2%20Agentes%20%7C%20RAG%20%7C%20Automa%C3%A7%C3%A3o%20%7C%20Full%20Stack&descSize=18&descAlignY=68" alt="Diego Hugo"/>
</p>

<!-- Selos -->
<p align="center">
  <img src="https://img.shields.io/badge/DISPON%C3%8DVEL-PARA%20PROJETOS-2ea44f?style=flat-square" alt="Disponível para projetos"/>
  <img src="https://komarev.com/ghpvc/?username=diegohugo570&label=PROFILE%20VIEWS&color=2ea44f&style=flat-square" alt="Profile views"/>
  <img src="https://img.shields.io/github/followers/diegohugo570?label=FOLLOWERS&style=flat-square&color=2ea44f" alt="Followers"/>
</p>

<h3 align="center">Construindo agentes de IA e automações que funcionam em produção</h3>

---

## 👨‍💻 Sobre mim

```text
Diego Hugo, AI Engineer e desenvolvedor Full Stack em São Paulo.
Foco em IA aplicada a negócios e marketing digital: agentes, RAG e automações.
Formação multidisciplinar: Engenharia Civil, Administração e Economia.

Stack principal: Python · LangGraph · n8n · FastAPI · Supabase · Docker
```

---

## 🛠️ Stack

| Categoria | Tecnologias |
|---|---|
| **IA & Agentes** | ![LangChain](https://img.shields.io/badge/LangChain-111827?style=flat-square) ![LangGraph](https://img.shields.io/badge/LangGraph-1f2937?style=flat-square) ![RAG](https://img.shields.io/badge/RAG-4B5563?style=flat-square) ![MCP](https://img.shields.io/badge/MCP-0F172A?style=flat-square) ![OpenAI](https://img.shields.io/badge/OpenAI-000000?style=flat-square&logo=openai&logoColor=white) ![Claude](https://img.shields.io/badge/Claude-CC785C?style=flat-square&logo=anthropic&logoColor=white) |
| **Automação** | ![n8n](https://img.shields.io/badge/n8n-FF6D00?style=flat-square&logo=n8n&logoColor=white) ![Make](https://img.shields.io/badge/Make-6D28D9?style=flat-square&logo=make&logoColor=white) ![Webhooks](https://img.shields.io/badge/Webhooks%20%2F%20APIs-374151?style=flat-square) |
| **Backend** | [![My Skills](https://skillicons.dev/icons?i=py,fastapi,nodejs,ts,php,laravel)](https://skillicons.dev) |
| **Frontend** | [![My Skills](https://skillicons.dev/icons?i=react,nextjs,js,tailwind,html,css)](https://skillicons.dev) |
| **Dados** | [![My Skills](https://skillicons.dev/icons?i=postgres,supabase,mysql,redis)](https://skillicons.dev) |
| **DevOps & Tools** | [![My Skills](https://skillicons.dev/icons?i=docker,git,github,vscode,vercel)](https://skillicons.dev) |

---

## ⭐ Projetos em destaque

### 🧠 Agente de Vendas Modular (n8n + Supabase + WhatsApp)

<p align="center">
  <img src="assets/Agente_de_Vendas_01.png" alt="Agente de Vendas" width="85%"/>
</p>

Arquitetura de 3 workflows: um **agente orquestrador** interpreta a intenção do cliente e aciona subfluxos de envio de imagens ou de link do produto. Memória por usuário, tool calling e dados sempre vindos do banco (o agente não inventa preços nem links).

`n8n` · `OpenAI` · `Supabase` · `Evolution API`

---

### 🤖 Agente de Atendimento com Follow-up (WhatsApp)

<p align="center">
  <img src="assets/potto-flow-agente-follow-up.png" alt="Agente com Follow-up" width="85%"/>
</p>

Atende texto, áudio (transcrição automática) e imagem, mantém memória da conversa, identifica a intenção do lead e dispara follow-ups após 10 minutos, 24 horas e 3 dias.

`n8n` · `LLM` · `Supabase` · `Z-API`

---

### 📚 RAG automático (Google Drive → Supabase Vector Store)

<p align="center">
  <img src="assets/fluxo-rag.png" alt="Pipeline RAG" width="85%"/>
</p>

Pipeline de ingestão: detecta novos PDFs no Drive, extrai o texto, faz chunking, gera embeddings e indexa no Supabase com metadados, deixando a base pronta para ser consultada por agentes.

`n8n` · `OpenAI Embeddings` · `Supabase (pgvector)`

---

### 🔌 Agente SDR com MCP (CRM como Tools)

<p align="center">
  <img src="assets/Agente_SDR_MCP_CRM.png" alt="Agente SDR com MCP" width="85%"/>
</p>

O CRM (Notion + Supabase) é exposto como ferramentas via **MCP Server**, e o agente decide sozinho quando buscar, qualificar ou encerrar leads, mantendo os dois sistemas sincronizados.

`n8n` · `MCP` · `Notion` · `Supabase`

---

### 📊 A Tríade — IA para análise de ações

Backend em **Python/FastAPI** que combina dados de mercado, notícias e LLMs com saída estruturada para apoiar a análise de ações. Arquitetura em camadas (API, Services, AI, Schemas) e containerizado.

`Python` · `FastAPI` · `Pydantic` · `Poetry` · `OpenAI` · `Docker`

> 🔗 [Código](https://github.com/diegohugo570/NOME-DO-REPOSITORIO)

---

## 🗂️ Mais projetos

<details>
<summary><b>🔁 Workflows n8n (clique para expandir)</b></summary>

<br>

| Workflow | O que faz |
|---|---|
| Resumo de e-mails | Resume o Gmail diariamente com pontos-chave e ações |
| Triagem de currículos | Lê PDFs do Drive, compara com a vaga e registra a nota no Sheets |
| Geração de contratos | Preenche modelo no Google Docs, converte em PDF e envia por WhatsApp |
| Agente financeiro | Registra, consulta e soma gastos por chat, com Supabase |
| Geração de leads | Google Maps → Outscraper → Google Sheets |
| Concessionária com IA | Busca veículos por critério e envia imagens via WhatsApp |
| Análise de ligações | Transcreve gravações VoIP e envia análise comercial por e-mail |
| Instagram | Respostas automáticas a DMs e comentários com IA |
| Recuperação de checkout | Funil de WhatsApp com timers para infoprodutos |

</details>

<details>
<summary><b>🌐 Projetos Full Stack</b></summary>

<br>

- **Antigravity Financial** — FastAPI, JWT, Redis (rate limiting), Cloudflare D1, dashboard financeiro
- **OCR Document API** — upload de imagens, OCR, busca textual (React + Node + PostgreSQL)
- **Sistema de Cadastro de Usuários** — Next.js, Node/Express, PostgreSQL, Docker + Traefik
- **Galeria de Imagens** — Node/TypeScript, Webpack, PostgreSQL, Docker Compose

</details>

<details>
<summary><b>🐍 Estudos práticos em Python & IA</b></summary>

<br>

Text2SQL Agent · API profissional com FastAPI · Prompt Packer · Persistent Chat History · Token Cost Calculator · Model Provider SDK · Simple Vector Store · Fine-Tuning Dataset Prepper · Token Usage Dashboard · CLI Assistant com agente

</details>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=diegohugo570&theme=github_dark" width="48%"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=diegohugo570&theme=github_dark" width="48%"/>
</p>

---

## 📫 Contato

<p align="center">
  <a href="https://linkedin.com/in/diegohrocha"><img src="https://img.shields.io/badge/LinkedIn-diegohrocha-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/diegohugo570"><img src="https://img.shields.io/badge/GitHub-diegohugo570-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>
