# ARIA: Análise Regulatória com Inteligência Artificial 🚀
### Vencedor do Case: *"GenAI para extrair conhecimento de dados complexos"*
**🥈 VENCEDOR DO SEGUNDO LUGAR no Hackathon Talento Tech 3.0 - Hacking for Good (2026)**

---

## 🌟 Visão Geral da Solução

![Visão Geral da ARIA](./assets/visao_geral.png)

A **ARIA** é uma plataforma de Inteligência Regulatória baseada em IA Generativa que automatiza a ingestão, interpretação e monitoramento contínuo de documentos científicos e normas técnicas. Transformamos bases de dados estáticas em um **"cérebro corporativo"** vivo, consultável em linguagem natural e baseado em evidências.

*   **Tecnologia RAG:** Garante respostas baseadas 100% em documentos reais, eliminando alucinações.
*   **Confiabilidade:** Foco total na rastreabilidade exigida pelo setor farmacêutico.

---

## 👤 O Desafio do Setor (Persona)

![Cenário: Endereçamento X Problema](./assets/desafio_setor.png)

> *"Hoje, a indústria farmacêutica precisa de automação na gestão de informações técnicas quando o alto volume de documentos complexos gera riscos de inconformidade e lentidão na tomada de decisão."*

### Exemplo Prático:
*   **Antes:** Renata gasta **15 horas por semana** lendo manualmente atualizações da ANVISA/FDA.
*   **Depois (com ARIA):** Às 8h da manhã, Renata recebe um **alerta com resumo executivo pronto**, destacando o impacto real nos produtos da empresa.

---

## 🚀 Diferenciais da Solução
1.  **RAG (Retrieval-Augmented Generation):** Respostas fundamentadas com citação de fonte (página/parágrafo).
2.  **Ingestão Proativa:** Monitoramento autônomo via **Amazon EventBridge** em órgãos reguladores.
3.  **Extração Especializada:** Integração com **Comprehend Medical** para identificar dosagens e relações clínicas complexas.

---

## 🏗️ Arquitetura da Solução (AWS Cloud Native)

![Diagrama de Arquitetura ARIA](./assets/arquitetura_solucao.png)

Uma arquitetura **100% serverless** dividida em quatro zonas funcionais (Borda, Roteamento, Ingestão e Inteligência):
*   **Segurança:** Proteção de borda com **AWS WAF** e CloudFront.
*   **Orquestração:** Fluxos gerenciados pelo **AWS Step Functions** com tratamento de erros via **Amazon SQS**.
*   **Cérebro de IA:** **Amazon Bedrock (Claude 3 Haiku)** integrado ao **OpenSearch Serverless** para busca vetorial.

### 📺 Vídeo Demonstração
[Assista ao vídeo da arquitetura e fluxo de dados](./arquitetura_github.mp4)

---

## 🧪 Validação e Prova de Conceito (PoC)

![Testes ARIA](./assets/poc_validacao.png)

O sistema foi validado com documentos reais, demonstrando a capacidade de extrair "insights" de textos densos e gerar respostas estruturadas.
*   **Checklist:** Processamento real, extração estruturada e rastreabilidade total via Step Functions.

---

## 📊 Impacto e Métricas de Sucesso

![Métricas de Sucesso](./assets/metricas_sucesso.png)


| Métrica | Cenário Tradicional | Com ARIA |
| :--- | :--- | :--- |
| **Tempo de Análise** | Dias ou Semanas | **Minutos ou Segundos** |
| **Risco de Compliance** | Alto (falha humana) | **Mínimo (Monitoramento 24/7)** |
| **Custo Operacional** | Alto (tarefas braçais) | **Baixo (IA processa o volume)** |

---

## 🌿 Sustentabilidade (ESG - Hacking for Good)

![Impacto Ambiental](./assets/sustentabilidade.png)

*   **Desmaterialização:** Fluxo digital com Resíduo Zero (eliminação de papel).
*   **Eficiência Energética:** Arquitetura **Serverless First** que minimiza o desperdício energético operando apenas sob demanda.

---

## 💰 FinOps e Roadmap Futuro

![Roadmap e FinOps](./assets/roadmap_futuro.png)

*   **Custo Atual (PoC):** ~$305,18/mês (Foco em OpenSearch).
*   **Estratégia de Escala:** Substituição pelo **RDS com pgvector**, reduzindo o custo fixo para aproximadamente **$15,00/mês**.
*   **Próximos Passos:** Implementação de **Amazon Cognito** (Segurança) e **Cache Semântico** com DynamoDB.

---

## 🤝 Time de Desenvolvimento (Grupo 4)

![Equipe Vencedora ARIA](./assets/foto_time.jpg)

*   **Fernanda Ferreira de Oliveira**
*   **Gustavo Dias Gomes**
*   **Melina Nascimento França**
*   **Tadeu Silva de Queiroz**
*   **Vinicio Rocha dos Reis**

---

## 🏢 Realização e Apoio
Projeto desenvolvido para o **Hackathon Talento Tech 3.0**, apresentado no **SENAI Santo Amaro**.

**Parceiros:**
Escola da Nuvem | AWS | TD SYNNEX | Dedalus | BRLink | Enkel | Darede | DreamSquad

