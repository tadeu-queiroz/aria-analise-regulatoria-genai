# ARIA — Inteligência Regulatória com IA Generativa 🚀

**Extração de Conhecimento em Dados Complexos**

🥈 **2º Lugar Geral — Hackathon Talento Tech 3.0 · Escola da Nuvem · Hacking for Good 2026**

[![AWS](https://img.shields.io/badge/AWS-Serverless-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)
[![Amazon Bedrock](https://img.shields.io/badge/Amazon_Bedrock-Claude_3_Haiku-7B2FBE?style=flat-square&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/bedrock/)
[![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)

</div>

---

## 🌟 Visão Geral do Projeto

[![Visão Geral](https://github.com/tadeu-queiroz/aria-analise-regulatoria-genai/blob/main/ativos/slides/Slide.png.jpg)](https://github.com/tadeu-queiroz/aria-analise-regulatoria-genai/blob/main/ativos/slides/Slide.png.jpg?raw=true)

A **ARIA** (anteriormente conhecida como *PharmaGen Insights*) é uma plataforma de Inteligência Regulatória avançada que automatiza todo o ciclo de vida de documentos técnicos — desde a leitura e interpretação até o acompanhamento contínuo de normas e publicações científicas. Com isso, transforma informações estáticas em um **"cérebro corporativo"** sempre atualizado e consultável.

Nascida no Hackathon Talento Tech 3.0 Escola da Nuvem 2026, a solução resolve o gargalo da leitura manual de milhares de páginas de editais, ensaios clínicos e resoluções, eliminando altos custos operacionais e riscos críticos de não conformidade.

---

## 👤 O Desafio do Setor

> *"A indústria farmacêutica trabalha com uma grande quantidade de documentos complexos. Sem automação, as decisões ficam mais lentas e há riscos de multas e sanções por erros na interpretação das normas."*

| | Cenário Tradicional | Cenário com ARIA |
|---|---|---|
| **Análise regulatória** | ~15h semanais de leitura manual (ANVISA/FDA) | Busca ativa e processamento autônomo |
| **Entrega ao analista** | Documento bruto para interpretar | Relatório Estratégico com impactos diretos |
| **Foco do profissional** | Leitura operacional | Inovação e segurança |

---

## 🚀 Diferenciais Estratégicos e Técnicos

- **RAG (Retrieval-Augmented Generation)** — respostas fundamentadas nos documentos carregados, com citação de fonte, página e parágrafo, essencial para auditorias.
- **Ingestão Híbrida**
  - *Reativa (Manual):* upload de PDFs (estudos, dossiês) via portal.
  - *Proativa (Autônoma):* busca ativa via API/Crawler em órgãos reguladores com Amazon EventBridge.
- **Extração Especializada** — Amazon Textract + Comprehend Medical para identificar entidades clínicas (dosagens, princípios ativos) e relações médicas complexas.
- **Human-in-the-Loop** — fluxos de aprovação integrados para validação de informações críticas por especialistas antes da indexação final.

---

## 🏗️ Arquitetura Cloud Native (AWS)

[![Arquitetura da Solução](https://github.com/tadeu-queiroz/aria-analise-regulatoria-genai/blob/main/ativos/slides/Slide4.png.jpg)](https://github.com/tadeu-queiroz/aria-analise-regulatoria-genai/blob/main/ativos/slides/Slide4.png.jpg?raw=true)

Desenhada sob os pilares do **AWS Well-Architected Framework**, garantindo integridade regulatória:

| Serviço AWS | Função |
|---|---|
| **Amazon S3** | Camadas Raw, Processed e Archive com Lifecycle, Versionamento e Object Lock |
| **AWS Step Functions** | Orquestração de fluxo com tratamento de erros via SQS |
| **Amazon Bedrock (Claude 3 Haiku)** | Geração contextual com busca semântica via Embeddings |
| **Amazon OpenSearch Serverless** | Índice vetorial para RAG |
| **Amazon Textract + Comprehend Medical** | Extração de entidades clínicas de documentos complexos |
| **Amazon EventBridge** | Ingestão proativa e agendamento de crawlers |
| **AWS KMS + CloudTrail** | Criptografia, auditoria e conformidade LGPD/HIPAA |
| **Amazon API Gateway + Lambda** | API REST serverless |

---

## 📺 Vídeo Demonstração

[![▶ Assistir Demonstração](https://img.shields.io/badge/▶_Assistir-Demonstração-red?style=for-the-badge)](docs/README.md)

---

## 🧪 Validação e Prova de Conceito (PoC)

[![PoC Validação](https://github.com/tadeu-queiroz/aria-analise-regulatoria-genai/blob/main/ativos/slides/poc_validacao.pdf.jpeg)](https://github.com/tadeu-queiroz/aria-analise-regulatoria-genai/blob/main/ativos/slides/poc_validacao.pdf.jpeg?raw=true)

O sistema foi validado com documentos reais, demonstrando capacidade de extrair insights de textos densos e gerar respostas estruturadas:

- ✅ Processamento de documentos reais
- ✅ Extração de insights estruturados
- ✅ Pipeline fim-a-fim funcionando
- ✅ Rastreabilidade via Step Functions

---

## 📱 Interface Web

[![Interface Web](https://github.com/tadeu-queiroz/aria-analise-regulatoria-genai/blob/main/ativos/slides/Slide9.png.jpg)](https://github.com/tadeu-queiroz/aria-analise-regulatoria-genai/blob/main/ativos/slides/Slide9.png.jpg?raw=true)

---

## 📊 Impacto e Métricas de Sucesso

| Dimensão | Impacto |
|---|---|
| **Agilidade** | Redução do tempo de análise de semanas para segundos |
| **Conformidade** | Monitoramento 24/7, mitigando riscos de multas e sanções |
| **Eficiência** | IA absorve o volume operacional, liberando talentos para análise |
| **Time-to-Market** | Resposta acelerada a mudanças regulatórias e novos estudos |

---

## 💰 FinOps e Viabilidade Econômica

[![FinOps](https://github.com/tadeu-queiroz/aria-analise-regulatoria-genai/blob/main/ativos/slides/Slide11.png.jpg)](https://github.com/tadeu-queiroz/aria-analise-regulatoria-genai/blob/main/ativos/slides/Slide11.png.jpg?raw=true)

- **Investimento Mensal (PoC):** estimado em **$305,18** via AWS Pricing Calculator
- **Estratégia de Escala:** substituição do OpenSearch por RDS com pgvector reduz o custo fixo para ~**$57,00/mês**
- **Governança:** monitoramento via AWS Budgets com alertas preditivos em 60%

---

## 🌿 Compromisso ESG (Hacking for Good)

Alinhada ao pilar de Sustentabilidade do AWS Well-Architected Framework:

- **Desmaterialização** — digitalização completa do fluxo regulatório, eliminando milhares de páginas físicas
- **Eficiência Energética (Serverless First)** — Lambda e serviços sob demanda garantem consumo apenas durante o processamento ativo, reduzindo drasticamente a pegada de carbono
- **Otimização de Recursos** — arquitetura desenhada para maximizar utilização de recursos compartilhados e eliminar infraestrutura ociosa

---

## 🆙 Roadmap

- **Fase 1:** Reforço de Segurança e Identidade com Amazon Cognito
- **Fase 2:** Otimização de Performance via Cache Semântico (DynamoDB)
- **Melhoria Contínua:** Benchmarking de precisão vs. custo por token

---

## 📄 Documentação Técnica

👉 [Acessar Apresentação Completa (PDF)](docs/)

---

## 🤝 Time de Desenvolvimento — Grupo 4

[![Equipe](https://github.com/tadeu-queiroz/aria-analise-regulatoria-genai/blob/main/assets/foto_equipe.jpg?raw=true)](https://github.com/tadeu-queiroz/aria-analise-regulatoria-genai/blob/main/assets/foto_equipe.jpg?raw=true)

| | |
|---|---|
| Fernanda Ferreira de Oliveira | Gustavo Dias Gomes |
| Melina Nascimento França | Tadeu Silva de Queiroz |
| Vinicio Rocha dos Reis | |

---

## 🏢 Realização e Apoio

Projeto desenvolvido para o **Hackathon Talento Tech 3.0 · Escola da Nuvem**, apresentado no **SENAI Santo Amaro (Suíço-Brasileira)**.

Empresas apoiadoras: **Escola da Nuvem · AWS · TD SYNNEX · Dedalus · BRLink · Enkel · Darede · DreamSquad**


