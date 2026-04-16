# 🎤 Roteiro de Apresentação: Projeto ARIA

Este roteiro foi desenvolvido para uma apresentação de aproximadamente **5 a 7 minutos**, focando em impacto, clareza técnica e valor de negócio.

---

## 🛝 Slide 1: Capa
**Fala:**
"Bom dia a todos! Nós somos o Grupo 4 e hoje temos o prazer de apresentar a **ARIA: Análise Regulatória com Inteligência Artificial**. Nossa solução foi desenvolvida para transformar a forma como a indústria farmacêutica lida com a complexidade regulatória, unindo tecnologia de ponta e conformidade."

---

## 🛝 Slide 2: Endereçamento X Problema
**Fala:**
"Para entender o valor da ARIA, precisamos olhar para o dia a dia de profissionais como a Renata. Hoje, um analista regulatório gasta, em média, **15 horas por semana** apenas lendo atualizações da ANVISA e novos ensaios clínicos. É um processo manual, lento e sujeito a falhas humanas que podem custar milhões em sanções. 
Com a ARIA, esse cenário muda: a Renata chega ao trabalho às 8h da manhã e já encontra um resumo executivo pronto, destacando exatamente o que mudou e qual o impacto direto nos produtos da empresa."

---

## 🛝 Slide 3: Visão Geral da Solução
**Fala:**
"Mas como fazemos isso? A ARIA não é apenas um chat comum. É uma plataforma de Inteligência Regulatória que utiliza **GenAI e RAG (Retrieval-Augmented Generation)**. 
O diferencial do RAG é que ele garante que a IA responda baseada **estritamente** nos documentos oficiais carregados. Isso elimina as famosas 'alucinações' da IA e garante total confiabilidade, com citação de fontes para cada resposta gerada."

---

## 🛝 Slide 4: Principais Benefícios e Medidas de Sucesso
**Fala:**
"Os ganhos são claros: reduzimos o tempo de análise de **dias para segundos**. O risco de compliance cai drasticamente com monitoramento 24/7. 
Além disso, nosso projeto nasce com o DNA **ESG**. Promovemos a desmaterialização total de processos e utilizamos uma arquitetura *Serverless First*, o que significa que só consumimos energia quando o sistema está processando, reduzindo a pegada de carbono da operação."

---

## 🛝 Slide 5: Arquitetura da Solução
**Fala:**
"Tecnicamente, a ARIA é 100% Cloud Native na AWS. Nossa arquitetura é dividida em quatro zonas:
1. **Borda:** Segurança total com WAF e CloudFront.
2. **Roteamento:** Orquestração inteligente com Step Functions.
3. **Ingestão:** Processamento automático de documentos via Textract e Comprehend Medical.
4. **Inteligência:** Onde o Amazon Bedrock e o OpenSearch Serverless trabalham juntos para entregar a busca vetorial e os insights."

---

## 🛝 Slide 6: Gravação da Demonstração
**Fala:**
"*(Inicie o vídeo)* Aqui vocês podem ver a ARIA em ação. Observem como o fluxo automático identifica novos documentos e como a interface permite consultas complexas em linguagem natural, entregando respostas estruturadas e prontas para a tomada de decisão."

---

## 🛝 Slide 7: Próximos Passos e Melhorias Futuras
**Fala:**
"Nosso roadmap é ambicioso. Na primeira semana, focaremos em segurança avançada com Amazon Cognito. Na segunda, implementaremos Cache Semântico para otimizar ainda mais os custos. 
Falando em custos, nossa PoC hoje custa cerca de $305 mensais, mas já temos o plano para reduzir isso para apenas **$57/mês** usando RDS com pgvector, tornando a ARIA viável para empresas de qualquer porte."

---

## 🛝 Slide 8: Perguntas e Respostas
**Fala:**
"Gostaríamos de agradecer à Escola da Nuvem, à AWS e a todos os parceiros por essa oportunidade. Estamos abertos agora para perguntas e para aprofundar em qualquer detalhe técnico ou de negócio. Muito obrigado!"

---

## 💡 Dicas para o Apresentador:
*   **Postura:** Mantenha a confiança, você é o especialista no projeto que venceu o 2º lugar!
*   **Tempo:** Não se prenda demais aos detalhes técnicos do Slide 5, a menos que perguntem. Foque no **valor** que a arquitetura entrega.
*   **Vídeo:** Certifique-se de que o vídeo está pronto para rodar sem travas.
