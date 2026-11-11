# Giovani Felippe Rodrigues

**Desenvolvedor backend Python · integrações, automação e IA aplicada**
Limeira, SP · [LinkedIn](https://www.linkedin.com/in/giovani-felippe-rodrigues-3031b949)

## Quem sou
Há mais de duas décadas trabalho com tecnologia, a maior parte delas na empresa da minha família (indústria de ferramentaria), onde sou responsável pela área de TI. Implantei um ERP e construí, em Python e PostgreSQL, automações e integrações que rodam em produção. Hoje também desenvolvo produtos próprios (um SaaS e uma plataforma de pagamentos) e estou concentrando minha carreira em **backend Python e IA aplicada**.

## Projetos em produção
Os códigos são privados (dados e clientes reais). Cada projeto terá um estudo de caso em texto.

| Projeto | O que faz | Tecnologias |
|---|---|---|
| **Automação fiscal e BI sobre um ERP** | Captura e triagem de notas fiscais por e-mail; conector com a API nacional de NFS-e (certificado digital, consulta incremental, conciliação automática com contas a pagar); camada de BI sobre um banco de cerca de 950 tabelas, com engenharia reversa sem documentação | Python, Flask, PostgreSQL, SQLAlchemy, Redis, APScheduler, Sentry |
| **Concilia (SaaS multi-cliente)** | Relatórios de horas e materiais, faturamento com prazos de recebimento e geração de PDF; assinatura mensal com Mercado Pago (webhooks, conciliação periódica, reembolso), validada com pagamentos reais | Python, PostgreSQL (Supabase), Google Cloud Run, Cloud Scheduler, Secret Manager, Resend |
| **Plataforma de eventos e cursos online** | Multi-tenant (um espaço por parceiro), pagamentos com Stripe Connect e Mercado Pago, comissão automática da plataforma, integrações com Hotmart e Google Calendar, limitação de requisições e conferência de webhooks | TypeScript, Node.js, MySQL, Docker, VPS Linux |

## Outros projetos
| Projeto | O que é | Status |
|---|---|---|
| Precificador | SaaS de organização financeira para criadores de cursos, integrando plataformas de venda por API; testes e CI | Em pausa |
| Comparador de preços de encartes | Foto do encarte, extração com IA de visão (Claude) e normalização de produtos | Em andamento |
| `doc-extract` | Extração estruturada de documentos com LLM, validações, pipeline (Prefect) e API (FastAPI) | Em construção |
| `rag-estudo` | Perguntas e respostas sobre documentos com embeddings e busca vetorial | Em construção |

## No que trabalho
- **Uso no dia a dia:** Python, Flask, PostgreSQL, MySQL, APIs REST, webhooks, Docker, Git, Redis, Google Cloud Run
- **Já pratiquei (exercícios):** RabbitMQ, Kubernetes, Terraform, microsserviços
- **Estudando agora:** FastAPI, testes (pytest, TDD), RAG e LLMs, orquestração com Prefect

## Como trabalho com IA
Uso Claude Code e outros assistentes todos os dias. Os projetos acima foram construídos com assistência de IA, sob minha direção e revisão, e valido o resultado com testes, scripts de auditoria e pagamentos reais de teste. Também treino programar sem ela. Nos projetos novos há uma seção "Como usei IA", com o que pedi, onde ela errou e como corrigi.
