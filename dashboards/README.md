# Dashboard de Vendas em Power BI

## Sobre o projeto

Este projeto foi desenvolvido com o objetivo de praticar análise de dados, visualização de informações e construção de dashboards no Power BI.

A proposta foi transformar uma base de vendas em um painel visual que permitisse analisar o desempenho comercial de forma clara, identificando tendências, categorias com maior resultado, produtos de destaque, lucro e distribuição geográfica das vendas.

Esse projeto faz parte da minha transição para a área de Dados e BI, sendo uma aplicação prática de conceitos como Power BI, Power Query, modelagem e análise exploratória.

---

## Objetivo

Criar um dashboard interativo para monitorar indicadores de vendas e gerar insights que auxiliem na tomada de decisão.

---

## Perguntas de negócio

Durante a análise, busquei responder perguntas como:

* Como as vendas evoluem ao longo do tempo?
* Quais categorias geram mais faturamento?
* Quais produtos são mais relevantes?
* Existe diferença entre faturamento e lucro?
* Como as vendas estão distribuídas geograficamente?

---

## Ferramentas utilizadas

- **Power BI**
- **Power Query**
- **DAX**
- **Base de dados em CSV no Kaggle**

---

## Estrutura do dashboard

O dashboard foi construído para apresentar uma visão geral das vendas e responder perguntas importantes de negócio.

### Indicadores principais (KPIs)
- **Faturamento Total**
- **Total de Pedidos**
- **Ticket Médio por Pedido**

### Análises visuais
- **Faturamento ao longo do tempo**
- **Faturamento por categoria**
- **Produtos por faturamento**
- **Lucro por categoria**
- **Distribuição geográfica das vendas**

### Filtros
- **Categoria**
- **Região**

---

## Etapas do desenvolvimento

### 1. Organização do projeto
Estruturei os arquivos em pastas para manter o projeto organizado:

- `dados/`
- `dashboard/`
- `imagens/`

### 2. Importação e tratamento dos dados
Importei a base CSV no Power BI e utilizei o Power Query para ajustar os tipos de dados.

Alguns pontos importantes do tratamento:
- ajuste de datas com localidade correta
- conversão de colunas numéricas
- organização dos campos para análise

### 3. Criação de medidas (DAX)
Foram criadas medidas para calcular os principais indicadores:

- **Faturamento** Faturamento = SUM(Vendas[Sales])  
- **Pedidos** Total de Pedidos = COUNT(Vendas[Order ID])
- **Ticket Médio** Ticket Médio = DIVIDE([Faturamento], [Total de Pedidos])

### 4. Construção do dashboard
Após a modelagem e criação das medidas, organizei os visuais com foco em:

* Leitura simples
* Análise rápida
* Clareza na apresentação dos dados

### 5. Ajustes visuais
Foram aplicados:
- padronização de títulos
- uso de cores para destaque
- segmentações em formato dropdown
- organização do layout para melhorar a experiência de usuário

---

## Principais insights encontrados

### 1. Crescimento das vendas ao longo do tempo
O gráfico de faturamento ao longo do tempo mostra uma leve queda inicial e, depois, uma recuperação com crescimento mais forte nos períodos seguintes.

**Insight:**  
As vendas passaram a apresentar uma tendência de crescimento, indicando uma melhora no desempenho comercial ao longo do tempo.

---

### 2. Tecnologia foi a categoria com maior faturamento

A categoria **Tecnologia** se destaca como a principal responsável pelo faturamento.

**Insight:**
Tecnologia é o principal motor de recita do negócio, indicando maior relevância estratégica.

---

### 3. Produtos com maior faturamento
Alguns produtos concentram grande parte do faturamento.

**Insight:**  
Existe concentração de receita em poucos produtos, indicando um padrão próximo à regra 80/20 (Curva ABC)

---

### 4. Lucro por categoria 
Apesar de algumas categorias apresentarem bom faturamento, o lucro não acompanha na mesma proporção.

**Insight:**  
Nem sempre vender mais significa lucrar mais, reforçando a importância de analisar a rentabilidade.

---

### 5. Concentração geográfica das vendas
As vendas estão concentrada em determinadas regiões.

**Insight:**  
Existe concentração geográfica das vendas, indicando possível oportunidade de expansão.

---

### 6. Indicadores Principais
Os KPIs mostram o panorama geral do negócio.

**Insight**
O ticket médio pode ser utilizado como estratégia para aumento de valor por pedido, através de ações como upsell e cross-sell.

---
## Fonte de dados
Base de dados disponível no Kaggle: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final?resource=download

## O que aprendi com esse projeto

Esse projeto foi foi fundamental para desenvolver habilidades práticas em:

- tratamento de dados no Power Query
- criação de medidas em DAX
- organização de layout no Power BI
- construção de dashboards mais claros e objetivos
- análise de dados com foco em gerar insights


Além da parte técnica, reforçou a importância de utilizar dashboard como uma ferramenta de comunicação visual e apoio à tomada de decisão.

---

## Arquivos do projeto

- `dashboard/dashboard_vendas.pbix`
- `dados/vendas.csv`
- `imagens/dashboard.png`

---

## Visual do Dashboard

![Dashboard Completo](/imagens/Dashboard_completo.png)

## Indicadores principais

![KPIs](/imagens/KPIs.png)

## Análise temporal

![Tendência](/imagens/Tendencia.png)

## Faturamento por categoria

![Categoria](/imagens/Categoria.png)

## Produtos com maior faturamento

![Top Produtos](/imagens/Top_produtos.png)

## Lucro por categoria

![Lucro](/imagens/Lucro.png)

---

## Distribuição geográfica

![Mapa](/imagens/Mapa.png)

---
## Possíveis melhorias futuras

* análise de margem de lucro (%)
* impacto de descontos no lucro
* segmentação por cliente
* comparação por região e período
---
### 📌 Considerações finais

Este projeto foi desenvolvido com foco em aprendizado prático e aplicação de conceitos de análise de dados.

Mais do que construir visualizações, o objetivo foi entender o comportamento dos dados e gerar insights relevantes para apoiar decisões de negócio.
---

---

## 👩‍💻 Autoria


Projeto desenvolvido por **Katia Souza**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/katiabarbosasouza/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:katiabarbosads@gmail.com)

