# ☁️ Infraestrutura como Código & Segurança (Cloud Foundation) 

Este diretório detalha os componentes de infraestrutura da ARIA, desenhados para serem resilientes, seguros e escaláveis seguindo o **AWS Well-Architected Framework**.

## 🛡️ Camada de Segurança e Governança
Para um projeto de Inteligência Regulatória, a integridade dos dados é inegociável:

* **AWS WAF:** Proteção da borda contra ataques comuns (OWASP Top 10) e controle de taxa para evitar abusos na API.
* **Amazon Cognito:** Implementado para gestão de identidade e acesso (MFA) dos analistas.
* **AWS IAM:** Políticas de "Least Privilege" para que os serviços Lambda acessem apenas os buckets S3 e as coleções do OpenSearch necessários.
* **Criptografia:** Dados em repouso via **KMS** e em trânsito via **TLS 1.2+**.

## ⚙️ Componentes Core (Serverless First)
A ARIA utiliza serviços gerenciados para reduzir o overhead operacional:

1.  **Orquestração:** AWS Step Functions para gerenciar o workflow de análise (S3 -> Textract -> Bedrock).
2.  **Vetorização:** Amazon OpenSearch Serverless para busca semântica eficiente.
3.  **Inteligência:** Amazon Bedrock (Modelos Claude 3) para processamento de linguagem natural.

## 💰 FinOps & Monitoramento
* **AWS Budgets:** Configurado para disparar alertas ao atingir 60% e 80% do orçamento mensal de $305.
* **CloudWatch:** Dashboards para monitoramento de latência das chamadas de IA e erros de processamento.

---
> **Nota:** Por questões de segurança, arquivos de configuração sensíveis (como templates CloudFormation e políticas de IAM específicas) estão em um repositório privado para evitar exposição de IDs de conta e ARNs.
