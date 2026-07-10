# Olá, sou Guilherme Grandim 👋

**Data Scientist & Analista de Dados** | Python · SQL · Power BI · Machine Learning · BI & Analytics · IA Generativa
 
📍 Campinas, SP
📧 gui.grandim@gmail.com · [LinkedIn](https://www.linkedin.com/in/guilherme-grandim) · [Portfólio](https://guigrandim.github.io/portifolio_projetos/)

---
 
## Sobre mim
 
Cientista de Dados e Analista de Dados especializado em projetos ponta a ponta — da exploração dos dados brutos até modelos em produção e dashboards estratégicos que suportam decisões de negócio com impacto mensurável.
 
Meu background em analytics de performance esportiva (Vasco da Gama, Cruzeiro, Corinthians) me treinou para trabalhar sob pressão com dados incompletos, entregar insights rápidos e comunicar resultados com clareza para stakeholders não técnicos.
 
Construindo portfólio de Data Science com metodologia **CRISP-DS**, focado em analytics de negócio, modelagem preditiva e soluções de BI em produção.
 
---

## Projetos em destaque

### 🏪 [Rossmann Store Sales — Previsão de Vendas com ML em Produção](https://github.com/guigrandim/rossmann_store_sales)
Diante do desafio da rede de farmácias Rossmann de planejar o orçamento de reformas de suas mais de 1.115 lojas, o CFO necessitava de previsões de vendas precisas para as próximas seis semanas, mitigando o erro das estimativas manuais e descentralizadas dos gerentes. Recebi a tarefa de desenvolver um modelo de Machine Learning robusto capaz de capturar as nuances de faturamento de cada filial, considerando fatores como sazonalidade, promoções e dias de fechamento. Para isso, a partir da metodologia CRISP-DS consttrui uma análise exploratória rigorosa (10 etapas) realizando engenharia de features com encoding cíclico, seleção via Boruta, comparação de 5 algoritmos com cross-validation temporal, tuning de XGBoost via Random Search e deploy de API Flask no Heroku integrada a bot do Telegram. Como resultado, entreguei um pipeline de previsão ponta a ponta com um MAPE geral estabilizado em ~13% e erro entre cenário pessimista e otimista de R$ 1,69 milhão em toda a rede (sobre R$ 284 milhões previstos) permitindo ao CFO mitigar desvios de planejamento financeiro e otimizar a alocação de Capex em reformas, protegendo o fluxo de caixa contra uma exposição desnecessária.

🔗 [**Bot no Telegram →**] (https://t.me/rossmann_gg_bot) *(envie o número da loja e receba a previsão)*

---

### 🫁 [Respiratory Diseases Classifier — Triagem de Doenças Respiratórias com ML](https://github.com/guigrandim/respiratory-diseases)
Diante do desafio da Health Bridge Solutions de otimizar o direcionamento de pacientes com desconforto respiratório, recebi a tarefa de informatizar a triagem em papel e criar um modelo de Machine Learning como baseline de apoio à decisão, classificando 5 categorias de doenças sem risco clínico. Para isso, utilizei dados do DATASUS como proxy no Amazon S3/Glue/Athena, treinei um modelo XGBoost multiclasse no SageMaker avaliando a incerteza preditiva pelas funções softmax e softprob, e desenvolvi um formulário digital em Streamlit integrado à inferência serverless via AWS Lambda. Como resultado, entreguei uma solução segura via IAM que apresentou 68% de acurácia e F1 ponderado de 0,67 em teste, enquanto o isolamento da lógica computacional do pipeline completo em arquitetura Serverless (Lambda) reduziu o custo operacional de nuvem (OPEX) para apenas R$ 0,02 por requisição, gerando uma economia de escala projetada de milhares de reais anuais frente a servidores ligados continuamente.

🔗 [[**App ao vivo →**](https://jlqsegnebs6r6sy7sn3ebxskxy0ihkkx.lambda-url.us-east-1.on.aws/ ) *(a primeira visita pode levar ~1-2 minutos para acordar o ECS)*

---

### 🎮 [BrasCo Gaming — Visão Estratégica & ROI](https://github.com/guigrandim/video_games_sales)
Diante da alta competitividade e dinamismo do mercado global de games, uma startup necessitava identificar quais fatores (como plataformas, gêneros e regiões) maximizam o sucesso comercial de um título para direcionar seus investimentos de forma assertiva. Recebi a tarefa de realizar uma análise de dados aprofundada sobre o histórico de vendas globais para mapear o comportamento do consumidor, ciclos de vida de consoles e assimetrias regionais de mercado. Para isso, conduzi uma análise exploratória robusta (EDA), tratei dados históricos de lançamentos, utilizei arquitetura medallion (Bronze/Silver/Gold), avaliei a correlação entre avaliações e performance financeira, e construí visualizações estratégicas focadas em tendências macro de consumo. Como resultado, entreguei um report analítico estruturado que identificou mercado da América do Norte concentrando 37% do market share global, a Microsoft como uma empresa com menor custo por ponto de score (US$ 0,32M) e defini a nota-alvo de 7,5 para mitigação de risco em novos lançamentos mitigando o risco de investimento em títulos com histórico de saturação de mercado.

🔗 [**App ao vivo →**](https://brasco-videogames-sales.streamlit.app) *(pode levar ~30s para inicializar)*

---

### ☕ [Coffee Shop Analytics — 11 Hipóteses de Negócio](https://github.com/guigrandim/coffe_shopping)
Diante da necessidade de uma rede de cafeterias de otimizar sua eficiência operacional e aumentar o faturamento diário, a gestão precisava entender o comportamento de compra dos clientes para evitar desperdícios de estoque e identificar gargalos de atendimento. Recebi a tarefa de analisar o histórico de transações financeiras e operacionais para mapear os horários de pico, os produtos mais rentáveis e os padrões de consumo cruzado. Para isso, realizei uma análise exploratória de dados (EDA) detalhada, limpei e estruturei os dados de vendas, avaliei a sazonalidade horária e semanal do faturamento e identifiquei a correlação entre categorias de produtos. Como resultado entreguei que o faturamento cresceu +103,8% (Jan→Jun) 100% via volume (ticket médio flat em R$4,69), identifiquei um pico de 36,7% da receita diária concentrado em 3 horas e categoria com ticket 5× maior subexplorada com recomendação de upsell estimada em +R$75 mil/ano.

🔗 [**Dashboard →**](https://guigrandim.github.io/coffe_shopping/)

---

### 🛵 [Curry Company — Dashboard de Visão Estratégica](https://github.com/guigrandim/curry_company_project)
Diante do crescimento acelerado do marketplace de delivery Curry Company, a diretoria executiva enfrentava dificuldades para acompanhar a operação em tempo real e monitorar a eficiência das três principais frentes: a empresa, os entregadores e os restaurantes. Recebi a tarefa de centralizar e estruturar os dados operacionais dispersos, criando uma ferramenta analítica unificada que permitisse à gestão tomar decisões táticas e estratégicas rápidas baseadas em métricas de performance. Para isso, limpei e transformei os dados brutos utilizando Pandas, realizei análises de geolocalização e eficiência de entregas, e desenvolvi um painel interativo em Streamlit dividido em visões específicas para cada pilar do negócio. Como resultado, entreguei um painel analítico centralizado que identificou um SLA de entrega em 69,4% (meta ≤30min) sobre 41.419 pedidos e apliquei um Random Forest que atingiu R² = 0,652 (vs. 0,428 da regressão linear), revelando que entregas simultâneas (20,5% de importância) é o principal driver do tempo de entrega.

🔗 [**App ao vivo →**](https://currycompanyproject-ggsolutions.streamlit.app) *(pode levar ~30s para inicializar)*

---

### 🤖 [Ensaios de Algoritmos de ML](https://github.com/guigrandim/ensaios_algoritmos_ml)
Diante do risco de subotimização e custos elevados em produção ao escolher algoritmos de Machine Learning sem um embasamento estatístico claro, times de dados necessitam de um framework padronizado para avaliar o comportamento de modelos sob diferentes cenários de complexidade. Recebi a tarefa de conduzir um ensaio tecnológico robusto para realizar o benchmarking de algoritmos de Classificação, Regressão e Agrupamento, mapeando rigorosamente o impacto do ajuste de hiperparâmetros. Para isso, estruturei um ambiente experimental em Python, manipulei diferentes conjuntos de dados (treino, validação e teste), implementei métricas de avaliação criteriosas (como F1-Score, RMSE e Silhouette) e avaliei o comportamento de modelos desde Árvores de Decisão até algoritmos de Ensemble. Como resultado, entreguei um repositório de governança e validação de modelos que identificou a Random Forest como lider na classificação (F1 = 0,9591, Acurácia 96,5%) a XGBoost lider na regressão (R² = 0,3678) e a KMeans (K=3) superando Affinity Propagation em clusterização (Silhouette = 0,2330), gerando um guia de boas práticas de tuning consolidado e eliminando custos ocultos de infraestrutura decorrentes de modelos superdimensionados (overfitting).

---

## 🛠️ Stack
 
```
Analytics & BI:       Power BI · Looker Studio · Streamlit · Plotly
Linguagens & Dados:   Python · SQL · Pandas · NumPy
Machine Learning:     XGBoost · LightGBM · Scikit-learn · Feature Engineering · Cross-Validation
Cloud (AWS):          S3 · Glue Catalog · Athena · SageMaker · Lambda · ECR · ECS/Fargate · IAM
Deploy & Infra:       Docker · Flask · Git · GitHub · Render
Metodologia:          CRISP-DS · ETL · EDA · Estatística Inferencial · A/B Testing
IA & LLMs:            Claude Code · MCP (Model Context Protocol) · AI Agents
```
 
---

## 📚 Em Estudo
 
```
☁️  Cloud: GCP (BigQuery · Looker)
```
---

## 🎓 Formação
 
| Curso | Instituição | Ano |
|---|---|---|
| MBA em Data Science e Analytics | Universidade de São Paulo (USP) | 2025 |
| Bacharelado em Engenharia da Computação | Universidade Cruzeiro do Sul | 2025 |
| Mestrado em Biodinâmica do Movimento Humano | Universidade Estadual de Campinas (UNICAMP) | 2015 |
| Bacharelado em Educação Física | Universidade Estadual de Campinas (UNICAMP) | 2012 |
 
---
 
## 📄 Publicações
 
5 artigos científicos publicados durante o Mestrado na UNICAMP — análise de performance esportiva e modelagem estatística aplicada ao futebol.
 
Coautor do prefácio: *Manual Estratégico para a(o) Fisiologista no Futebol* (2026) · ISBN 978-65-02-03727-0
 
---
