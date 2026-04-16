# ARIA | Inteligência Regulatória com IA Generativa ⚖️ 🚀
**Solução Vencedora: "Extração de Conhecimento em Dados Complexos"**

🥈 **2º LUGAR GERAL** no Hackathon Talento Tech 3.0 - Escola da Nuvem - Hacking for Good 2026.

---

## 🌟 Visão Geral do Projeto

<p align="center">
  <img src="./assets/slides/slide-03.png" alt="Visão Geral da Solução" width="800">
</p>

A **ARIA** (anteriormente concebida como *PharmaGen Insights*) é uma plataforma de **Inteligência Regulatória** de última geração. Ela automatiza o ciclo completo de documentos técnicos — desde a ingestão e interpretação até o monitoramento contínuo de normas e publicações científicas — transformando dados estáticos em um **"cérebro corporativo"** vivo e consultável.

Nascida no **Hackathon Talento Tech 3.0** Escola da Nuvem 2026, a solução resolve o gargalo da leitura manual de milhares de páginas de editais, ensaios clínicos e resoluções, eliminando altos custos operacionais e riscos críticos de não conformidade.

### 👤 O Desafio do Setor (Persona)
> "A indústria farmacêutica lida com um volume massivo de documentos complexos. A falta de automação gera lentidão na tomada de decisão e riscos reais de multas e sanções por falhas na interpretação de normas."

### 💡 Transformação na Prática

<p align="center">
  <img src="./assets/slides/slide-02.png" alt="Endereçamento X Problema" width="800">
</p>

*   **Cenário Tradicional:** Analistas dedicam ~15h semanais à leitura manual de atualizações da ANVISA/FDA para evitar sanções.
*   **Cenário com ARIA:** O sistema realiza a busca ativa e o processamento autônomo. O analista recebe um **Relatório Estratégico** com impactos diretos, permitindo foco total em inovação e segurança.

---

## 🚀 Diferenciais Estratégicos e Técnicos

A ARIA utiliza um pipeline inteligente que garante **rastreabilidade total** e **explicabilidade**:

1.  **RAG (Retrieval-Augmented Generation):** Respostas fundamentadas estritamente nos documentos carregados, com citação direta de **fonte, página e parágrafo**, essencial para auditorias.
2.  **Ingestão Híbrida:** 
    *   **Reativa (Manual):** Upload de PDFs (estudos, dossiês) via portal.
    *   **Proativa (Autônoma):** Busca ativa via API/Crawler em órgãos reguladores (Amazon EventBridge).
3.  **Extração Especializada:** Integração de **Amazon Textract** com **Comprehend Medical** para identificar entidades clínicas (dosagens, princípios ativos) e relações médicas complexas.
4.  **Human-in-the-Loop:** Fluxos de aprovação integrados para que informações críticas sejam validadas por especialistas antes da indexação final.

---

## 🏗️ Arquitetura Cloud Native (AWS)

<p align="center">
  <img src="./assets/slides/slide-05.png" alt="Arquitetura da Solução" width="800">
</p>

Desenhada sob os pilares do **AWS Well-Architected Framework**, garantindo integridade regulatória:

*   **Armazenamento Inteligente:** Camadas de dados no **Amazon S3** (Raw, Processed, Archive) com políticas de Lifecycle, Versionamento e **Object Lock**.
*   **Orquestração de Fluxo:** Gerenciada pelo **AWS Step Functions**, tratando ramificações críticas e erros via **Amazon SQS**.
*   **Núcleo de IA:** **Amazon Bedrock** (Claude 3 Haiku) para geração contextual, integrado ao **Amazon OpenSearch Serverless** para busca semântica via Embeddings.
*   **Segurança e Governança:** Criptografia via **KMS**, trilha de auditoria com **CloudTrail** e conformidade com **LGPD/HIPAA**.

---

## 📺 Demonstração da Solução

<p align="center">
  <img src="./assets/slides/slide-06.png" alt="Gravação da Demonstração" width="800">
</p>

Veja a ARIA processando documentos e gerando insights em tempo real:

<video src="arquitetura_github.mp4" controls width="100%"></video>

---

## 📊 Métricas de Valor e Impacto

<p align="center">
  <img src="./assets/slides/slide-04.png" alt="Principais Benefícios e Medidas de Sucesso" width="800">
</p>

*   **Agilidade:** Redução do tempo de análise de semanas para segundos.
*   **Conformidade:** Monitoramento 24/7, mitigando riscos de multas e sanções.
*   **Eficiência:** IA processando o volume braçal, liberando talentos para tarefas analíticas.
*   **Time-to-Market:** Aceleração na resposta a mudanças regulatórias e novos estudos.

---

## 💰 FinOps e Viabilidade Econômica

<p align="center">
  <img src="./assets/slides/slide-07.png" alt="Próximos Passos e FinOps" width="800">
</p>

*   **Investimento Mensal (PoC):** Estimado em $305,18 via AWS Pricing Calculator.
*   **Estratégia de Escala:** Proposta de substituição do OpenSearch por **RDS com pgvector**, reduzindo o custo fixo para aproximadamente **$57,00/mês**.
*   **Governança:** Monitoramento via **AWS Budgets** com alertas preditivos em 60%.

---

## 🌿 Compromisso ESG (Hacking for Good)

*   **Desmaterialização:** Digitalização completa do fluxo regulatório (Resíduo Zero).
*   **Eficiência Energética:** Arquitetura **Serverless First**, minimizando o desperdício energético.
*     AWS Well-Architected suntentabilidade

---

## 🆙 Evolução e Roadmap

*   **Fase 1:** Reforço de Segurança e Identidade com **Amazon Cognito**.
*   **Fase 2:** Otimização de Performance via **Cache Semântico** (DynamoDB).
*   **Melhoria Contínua:** Benchmarking de precisão vs. custo por token.


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
