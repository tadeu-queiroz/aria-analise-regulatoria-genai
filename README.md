# ARIA | Inteligência Regulatória & GenAI ⚖️ 🚀
**🥈 2º Lugar no Hackathon Talento Tech 3.0 (2026)**
*Case Vencedor: "GenAI para extrair conhecimento de dados complexos"*

---

## 🌟 Sobre o Projeto
A **ARIA** é uma solução de ponta desenvolvida para a indústria farmacêutica. Ela resolve um dos maiores gargalos do setor: o tempo gasto na leitura e conformidade de normas técnicas (ANVISA/FDA).

### 💡 A Solução (Visão de Negócio)
* **Problema:** Analistas perdem cerca de **15h semanais** em leituras manuais.
* **Impacto ARIA:** Automação completa do monitoramento. O sistema processa atualizações às 06h e entrega um resumo estratégico às 08h, eliminando riscos de inconformidade e otimizando a tomada de decisão.

---

## 🏗️ Arquitetura da Solução (AWS Cloud Native)
O desenho técnico prioriza segurança, escalabilidade e o **AWS Well-Architected Framework**.

![Diagrama de Arquitetura](./assets/Arquitetura%20-%20ARIA.png)

### 🛠️ Diferenciais Técnicos implementados:
* **RAG (Retrieval-Augmented Generation):** Uso de **Amazon Bedrock (Claude 3)** para respostas precisas com citação de fontes, evitando alucinações.
* **Busca Vetorial:** **Amazon OpenSearch Serverless** para alta performance em grandes volumes de dados.
* **Ingestão Inteligente:** Fluxo orquestrado por **AWS Step Functions**, integrando **Amazon Textract** e **Comprehend Medical**.
* **Frontend:** Protótipo funcional desenvolvido em **HTML5 e CSS3** (disponível na pasta `src`).

---

## 💰 Estratégia FinOps (Gestão de Custos)
Demonstramos maturidade técnica ao planejar a viabilidade econômica do projeto:
* **Custo Estimado:** $305,18/mês (Arquitetura Robust).
* **Otimização de Escala:** Roadmap para redução para **$57,00/mês** utilizando RDS + pgvector.
* **Governança:** Monitoramento via **AWS Budgets** com alertas de 60%.
---

## 📊 Métricas e Validação
* **Precisão de Extração:** 98% de acerto na identificação de dosagens e princípios ativos (PoC).
* **Eficiência Operacional:** Redução de 80% no tempo de triagem de novos documentos.
* **Escalabilidade:** Arquitetura preparada para processar +1.000 documentos simultâneos via Step Functions.

---

## 📁 Estrutura do Meu Repositório
Navegue pelas pastas para conferir os entregáveis técnicos:
* 📂 [**Código Frontend**](./src/): Protótipo da interface de usuário.
* 📂 [**Documentação**](./docs/): Slides da apresentação e PDF do case.

  
<video src="./video/demonstracao.webm" controls width="100%"></video>

## 🤝 Equipe (Grupo 4)
* Fernanda Ferreira de Oliveira
* Gustavo Dias
* Melina Nascimento França
* **Tadeu Silva de Queiroz**
* Vinicio Rocha dos Reis

---

### 🏢 Realização e Apoio
**SENAI Santo Amaro (Suíço-Brasileira)**
*Parceiros:* Escola da Nuvem, AWS, TD SYNNEX, Dedalus, BRLink, Enkel, Darede.
