# Olá, sou Guilherme Grandim 👋

**Data Scientist & Analista de Dados** | Python · SQL · AWS · Power BI · Machine Learning · BI & Analytics · IA Generativa
 
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
O CFO da Rossmann precisava de previsões de vendas para as próximas seis semanas em 1.115+ lojas para substituir estimativas manuais dos gerentes e planejar o orçamento de reformas com mais precisão.

- EDA em 10 etapas via CRISP-DS, com encoding cíclico para sazonalidade e seleção de features via Boruta
- Comparação de 5 algoritmos com cross-validation temporal; XGBoost ajustado via Random Search
- API Flask no Heroku com bot de Telegram para consulta de previsões por filial

Resultado: MAPE de ~13%; diferença entre cenário pessimista e otimista de R$ 1,69 milhão sobre R$ 284 milhões previstos para toda a rede.

🔗 [**Bot no Telegram →**](https://t.me/rossmann_gg_bot) *(envie o número da loja e receba a previsão)*

---

### 🫁 [Respiratory Diseases Classifier — Triagem de Doenças Respiratórias com ML](https://github.com/guigrandim/respiratory-diseases)
A Health Bridge Solutions precisava otimizar o direcionamento de pacientes com desconforto respiratório, substituindo a triagem em papel por um modelo de ML capaz de classificar 5 categorias de doenças sem risco clínico.

- Dados do DATASUS como proxy, ingeridos e consultados via Amazon S3, Glue e Athena
- XGBoost multiclasse treinado no SageMaker com avaliação de incerteza preditiva via softmax e softprob
- Formulário digital em Streamlit com inferência serverless via Lambda e controle de acesso por IAM

Resultado: 68% de acurácia e F1 ponderado de 0,67 em teste; R$ 0,02 por requisição, com economia projetada de milhares de reais anuais frente a servidores contínuos.

🔗 [**App ao vivo →**](https://jlqsegnebs6r6sy7sn3ebxskxy0ihkkx.lambda-url.us-east-1.on.aws/ ) *(a primeira visita pode levar ~1-2 minutos para acordar o ECS)*

---

### 🎮 [BrasCo Gaming — Visão Estratégica & ROI](https://github.com/guigrandim/video_games_sales)
A BrasCo Gaming precisava identificar quais fatores maximizam o sucesso comercial de um título antes de alocar investimentos em novos lançamentos.

- EDA sobre histórico de vendas globais com arquitetura medallion (Bronze/Silver/Gold) para tratamento e camadas de dados
- Análise de correlação entre avaliações de crítica e performance financeira por plataforma, gênero e região
- Visualizações estratégicas focadas em tendências macro de consumo e ciclos de vida de consoles

Resultado: América do Norte concentra 37% do market share global; Microsoft apresenta o menor custo por ponto de score (US$ 0,32M); nota-alvo de 7,5 definida para mitigação de risco em novos lançamentos.

🔗 [**App ao vivo →**](https://brasco-videogames-sales.streamlit.app) *(pode levar ~30s para inicializar)*

---
### ⚡ [Análise de Compras Públicas de Componentes Elétricos](https://github.com/guigrandim/eletric_supply)
A área de Suprimentos de uma distribuidora de energia precisava entender os padrões de compra de componentes e condutores elétricos para negociar melhor com fornecedores e projetar o gasto do próximo exercício fiscal.

- Pipeline via API do ComprasNet com 164.680 registros de contratações públicas (CATMAT 59 e 61, 2021-2026) em schema estrela no SQLite
- EDA com teste de 4 hipóteses estatísticas sobre elasticidade de preço, sazonalidade e concentração de fornecedores
- Comparação de modelos de projeção trimestral: naive sazonal, XGBoost e Holt-Winters

Resultado: Economia potencial de R$492 milhões (≈31% do gasto total) ao segmentar itens por elasticidade; sazonalidade de jan-fev identificada como orçamentária, não de mercado; compras irregulares com maior dependência de fornecedor (ρ=-0,458); projeção de gasto 2027 de ≈R$368,4 milhões com naive sazonal superando XGBoost (MAPE 17,6% vs. 20,0%).

🔗 [**App ao vivo →**](https://eletricsupply.streamlit.app) *(pode levar ~30s para inicializar)*

---

### ☕ [Coffee Shop Analytics — 11 Hipóteses de Negócio](https://github.com/guigrandim/coffe_shopping)
A gestão de uma rede de cafeterias precisava entender o comportamento de compra dos clientes para evitar desperdício de estoque, identificar gargalos de atendimento e direcionar esforços de venda.

- EDA sobre histórico de transações com limpeza e estruturação dos dados de vendas
- Análise de sazonalidade horária e semanal do faturamento
- Mapeamento de correlação entre categorias de produtos e padrões de consumo cruzado

Resultado: Faturamento cresceu +103,8% (Jan→Jun) integralmente via volume (ticket médio flat em R$4,69); 36,7% da receita diária concentrada em 3 horas; categoria com ticket 5× maior subexplorada, com potencial de upsell estimado em +R$75 mil/ano.

🔗 [**Dashboard →**](https://guigrandim.github.io/coffe_shopping/)

---

### 🛵 [Curry Company — Dashboard de Visão Estratégica](https://github.com/guigrandim/curry_company_project)
A diretoria da Curry Company não tinha visibilidade em tempo real sobre as três frentes da operação: a empresa, os entregadores e os restaurantes.

- Limpeza e transformação dos dados brutos com Pandas, com análises de geolocalização e eficiência de entregas
- Painel interativo em Streamlit com visões segmentadas por pilar do negócio
- Random Forest para identificar os drivers do tempo de entrega

Resultado: SLA de entrega em 69,4% (meta ≤30min) sobre 41.419 pedidos; Random Forest com R²=0,652 vs. 0,428 da regressão linear; entregas simultâneas apontadas como principal driver (importância de 20,5%).

🔗 [**App ao vivo →**](https://currycompanyproject-ggsolutions.streamlit.app) *(pode levar ~30s para inicializar)*

---

### 🤖 [Ensaios de Algoritmos de ML](https://github.com/guigrandim/ensaios_algoritmos_ml)
Times de dados raramente têm um benchmark estruturado para escolher algoritmos com base em evidência estatística. Este repositório padroniza esse processo para Classificação, Regressão e Agrupamento.

- Ambiente experimental em Python com conjuntos de dados separados em treino, validação e teste
- Avaliação com métricas por tarefa: F1-Score e Acurácia (classificação), RMSE e R² (regressão), Silhouette (agrupamento)
- Benchmarking de Árvores de Decisão a algoritmos de Ensemble, com mapeamento do impacto de hiperparâmetros

Resultado: Random Forest líder em classificação (F1=0,9591, Acurácia 96,5%); XGBoost líder em regressão (R²=0,3678); KMeans (K=3) superando Affinity Propagation em clusterização (Silhouette=0,2330); guia consolidado de boas práticas de tuning para evitar overfitting em produção.

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
