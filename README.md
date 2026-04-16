# ARIA | Inteligência Regulatória com IA Generativa ⚖️ 🚀
**Solução Vencedora: "Extração de Conhecimento em Dados Complexos"**

🥈 **2º LUGAR GERAL** no Hackathon Talento Tech 3.0 - Hacking for Good (2026).

---

## 🌟 Visão Geral do Projeto

A **ARIA** é uma plataforma inovadora de **Inteligência Regulatória** que utiliza o poder da IA Generativa para automatizar o ciclo completo de documentos técnicos: desde a ingestão e interpretação até o monitoramento contínuo de normas e publicações científicas.

Nascida no **Hackathon Talento Tech 3.0**, a ARIA converte repositórios estáticos (PDFs, editais e dossiês clínicos) em um **Ecossistema de Conhecimento Ativo**, permitindo consultas em linguagem natural com total embasamento em evidências reais.

### 👤 O Desafio do Setor (Persona)
> "A indústria farmacêutica enfrenta um gargalo crítico: a gestão manual de um volume massivo de documentos técnicos. Isso gera riscos de conformidade, atrasos estratégicos e uma carga operacional insustentável para os analistas."

### 💡 Transformação na Prática
*   **Cenário Tradicional:** Um analista dedica cerca de **15 horas semanais** à leitura manual de atualizações da ANVISA e novos estudos para evitar sanções.
*   **Cenário com ARIA:** O sistema monitora fontes oficiais de forma autônoma. Às 06:00, a ARIA processa as novidades; às 08:00, o analista recebe um **Relatório Estratégico** com os impactos diretos nos produtos da companhia, eliminando o trabalho braçal.

---

## 🚀 Diferenciais Estratégicos

A ARIA se destaca por ir além de uma simples ferramenta de busca, integrando:

1.  **RAG (Retrieval-Augmented Generation):** Respostas fundamentadas exclusivamente nos documentos da empresa, com citação precisa de fonte (página e parágrafo), garantindo segurança e zero alucinação.
2.  **Monitoramento Proativo:** Integração com **Amazon EventBridge** para rastrear e capturar atualizações de órgãos como ANVISA e FDA em tempo real.
3.  **Processamento Especializado:** Uso combinado de **Amazon Textract** e **Comprehend Medical** para extração inteligente de dosagens, substâncias e correlações clínicas.

---

## 🏗️ Arquitetura Cloud Native (AWS)

Desenhada sob os pilares do **AWS Well-Architected Framework**, nossa arquitetura garante alta disponibilidade e escalabilidade:

*   **Ingestão e Armazenamento:** Fluxo via API Gateway e S3, com políticas de retenção e integridade regulatória (Object Lock).
*   **Orquestração de Processos:** Fluxos gerenciados pelo **AWS Step Functions**, com tratamento de erros via **Amazon SQS**.
*   **Núcleo de Inteligência:** **Amazon Bedrock** (Claude 3 Haiku) para processamento ágil, integrado ao **Amazon OpenSearch Serverless** para indexação vetorial.
*   **Segurança e Governança:** Proteção de borda com **AWS WAF** e criptografia de ponta a ponta.

<p align="center">
  <img src="./assets/Arquitetura%20-%20ARIA.png" alt="Arquitetura Técnica ARIA" width="800">
</p>

---

## 📺 Demonstração da Solução

Veja como a ARIA simplifica a análise de documentos complexos:

<video src="arquitetura_github.mp4" controls width="100%"></video>

---

## 📊 Métricas de Valor e Impacto

*   **Agilidade:** Redução drástica no tempo de triagem (de semanas para segundos).
*   **Conformidade:** Monitoramento ininterrupto (24/7), mitigando riscos regulatórios.
*   **Eficiência:** Redução de custos operacionais ao automatizar tarefas repetitivas de alto volume.
*   **Precisão:** Insights padronizados e totalmente rastreáveis.

---

## 🧪 Validação Técnica (PoC)

Nossa Prova de Conceito foi testada com documentação real do setor, comprovando a eficácia na extração de insights estruturados a partir de textos densos e técnicos.

---

## 💰 FinOps e Sustentabilidade Financeira

Planejamos a viabilidade do projeto com foco em governança de custos:
*   **Investimento Mensal (PoC):** Estimado em $305,18 via AWS Pricing Calculator.
*   **Estratégia de Escala:** Proposta de substituição do OpenSearch por **RDS com pgvector**, reduzindo o custo fixo para aproximadamente **$57,00/mês**.
*   **Controle de Gastos:** Implementação de **AWS Budgets** com alertas preditivos em 60% do teto orçamentário.

---

## 🌿 Compromisso ESG (Hacking for Good)

A ARIA contribui diretamente para metas de sustentabilidade:
*   **Desmaterialização:** Digitalização completa do fluxo regulatório, poupando milhares de impressões.
*   **Eficiência Energética:** Arquitetura **Serverless First** (AWS Lambda), garantindo consumo de recursos apenas durante o processamento ativo.

---

## 🆙 Evolução e Roadmap

*   **Fase 1:** Reforço de Segurança e Identidade com **Amazon Cognito**.
*   **Fase 2:** Otimização de Performance e Custo via **Cache Semântico** (DynamoDB).
*   **Melhoria Contínua:** Benchmarking de precisão vs. custo por token para refinamento do modelo.

---

## 📄 Documentação Técnica
👉 [**Acessar Apresentação Completa (PDF)**](./docs/Apresentação%20Hackathon%202026.pdf)

---

## 🤝 Time de Desenvolvimento (Grupo 4)

<p align="center">
  <img src="./assets/foto_equipe.jpg" alt="Equipe Vencedora ARIA" width="600">
</p>

*   **Fernanda Ferreira de Oliveira**
*   **Gustavo Dias Gomes**
*   **Melina Nascimento França**
*   **Tadeu Silva de Queiroz**
*   **Vinicio Rocha dos Reis**

---

## 🏢 Realização e Apoio

Projeto desenvolvido para o **Hackathon Talento Tech 3.0**, apresentado no **SENAI Santo Amaro (Suíço-Brasileira)**.

**Parceiros Estratégicos:**
Escola da Nuvem, AWS, TD SYNNEX, Dedalus, BRLink, Enkel, Darede.
