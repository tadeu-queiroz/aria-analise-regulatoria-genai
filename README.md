# ARIA | Inteligência Regulatória & GenAI ⚖️ 🚀

<p align="center">
  <img src="./assets/Arquitetura%20-%20ARIA.png" alt="ARIA Logo" width="600">
</p>

> **🥈 Vencedor do 2º Lugar - Hackathon Talento Tech 3.0 (2026)**  
> *Case: "GenAI para extrair conhecimento de dados complexos e conformidade farmacêutica"*

---

## 🌟 Visão Geral

A **ARIA (Análise Regulatória com Inteligência Artificial)** é uma plataforma de vanguarda baseada em **IA Generativa** que automatiza a ingestão, interpretação e o monitoramento contínuo de documentos científicos e normas técnicas.

Desenvolvida durante o **Hackathon Talento Tech 3.0**, a solução transforma bases de dados estáticas (PDFs de editais, dossiês e ensaios clínicos) em um **"cérebro corporativo"** vivo, consultável em linguagem natural e totalmente fundamentado em evidências.

### 💡 O Problema vs. A Solução

| Cenário | Antes (Manual) | Depois (Com ARIA) |
| :--- | :--- | :--- |
| **Esforço** | Analistas gastam ~15h/semana lendo atualizações. | Monitoramento autônomo e proativo. |
| **Rotina** | Busca manual em sites da ANVISA/FDA. | Ingestão automática às 06:00 da manhã. |
| **Entrega** | Risco de lentidão e inconformidade. | Resumo estratégico pronto às 08:00 na mesa do analista. |

---

## 🚀 Diferenciais da Solução

Diferente de ferramentas de busca comuns, a ARIA utiliza tecnologias de ponta para garantir precisão e automação:

1.  **RAG (Retrieval-Augmented Generation):** Garante que as respostas da IA sejam baseadas estritamente nos documentos carregados, eliminando "alucinações" e fornecendo citações diretas de fonte (página/parágrafo).
2.  **Ingestão Proativa:** Utiliza o **Amazon EventBridge** para monitorar e baixar atualizações de órgãos reguladores de forma autônoma.
3.  **Extração Especializada:** Integração do **Amazon Textract** com **Comprehend Medical** para identificar dosagens, princípios ativos e relações clínicas complexas.

---

## 🏗️ Arquitetura Técnica (AWS Cloud Native)

A solução foi desenhada sob o **AWS Well-Architected Framework**, priorizando segurança, escalabilidade e eficiência:

*   **Camada de Ingestão:** AWS API Gateway + S3 (com políticas de Lifecycle e Object Lock).
*   **Orquestração:** **AWS Step Functions** gerencia o fluxo de processamento e filas **Amazon SQS**.
*   **Cérebro de IA:** **Amazon Bedrock** (Claude 3 Haiku) integrado ao **Amazon OpenSearch Serverless** para busca vetorial.
*   **Segurança:** Proteção de borda com **AWS WAF** e criptografia total de dados.

---

## 📺 Demonstração em Vídeo

Confira a ARIA em ação processando documentos e gerando insights:

<video src="arquitetura_github.mp4" controls width="100%"></video>

---

## 💰 FinOps e Viabilidade Econômica

Demonstramos maturidade técnica ao planejar a viabilidade econômica do projeto:

*   **Custo Mensal Estimado:** $305,18 (Arquitetura Robust).
*   **Roadmap de Otimização:** Proposta de redução para **$57,00/mês** utilizando RDS + pgvector para empresas menores.
*   **Governança:** Monitoramento via **AWS Budgets** com alertas de 60% do orçamento.

---

## 🌿 Sustentabilidade (ESG - Hacking for Good)

*   **Redução de Resíduos:** Eliminação física de milhares de páginas de papel no fluxo regulatório.
*   **Serverless First:** O uso de **AWS Lambda** garante que a computação ocorra apenas sob demanda, minimizando o desperdício energético.

---

## 🆙 Próximos Passos

- [ ] **Semana 1:** Implementação do **Amazon Cognito** para gestão de identidade.
- [ ] **Semana 2:** Implementação de **Cache Semântico** com DynamoDB para redução de custos.
- [ ] **Contínuo:** Avaliação de Qualidade da IA (Precisão x Custo por Token).

---

## 🤝 Equipe (Grupo 4)

*   **Fernanda Ferreira de Oliveira**
*   **Gustavo Dias Gomes**
*   **Melina Nascimento França**
*   **Tadeu Silva de Queiroz**
*   **Vinicio Rocha dos Reis**

---

## 🏢 Realização e Apoio

**SENAI Santo Amaro (Suíço-Brasileira)**  
*Parceiros:* Escola da Nuvem, AWS, TD SYNNEX, Dedalus, BRLink, Enkel, Darede.
