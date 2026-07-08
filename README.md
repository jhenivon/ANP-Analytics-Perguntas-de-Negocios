# 📊 Análises de Negócio

# ANP Analytics

Projeto de Analytics desenvolvido a partir da tabela `gold_combustivel`, produzida no projeto ETL_Preco_Combustivel_SQL.

O objetivo é responder perguntas de negócio utilizando SQL no Databricks e visualizar os resultados através de gráficos.

## Perguntas Respondidas

1. Quais estados apresentam o maior preço médio dos combustíveis em 2025?
2. Quais estados apresentam o menor preço médio dos combustíveis em 2025?
3. Como os preços evoluíram ao longo do tempo em 2025??
4. Qual combustível possui o maior preço médio?
5. Em quais estados a diferença média entre Gasolina e Etanol é maior?
6 Quais bandeiras apresentam os maiores preços médios dos combustíveis em 2025?

---

## 1. Quais estados apresentam o maior preço médio dos combustíveis em 2025?

![Estados Mais Caros](img/01_estados_mais_caros.png)

---

## 2. Quais estados apresentam o menor preço médio dos combustíveis em 2025?

![Estados Mais Baratos](img/02_estados_mais_baratos.png)

---

## 3. Como os preços evoluíram ao longo do tempo em 2025??

![Preço Médio por Produto](img/03_preco_medio_produto.png)

---

## 4. Qual combustível possui o maior preço médio?

![Gasolina vs Etanol](img/04_gasolina_vs_etanol.png)

---

## 5 - Em quais estados a diferença entre Gasolina e Etanol é maior?

![Evolução Mensal](img/05_evolucao_mensal.png)

---

## 6. Quais bandeiras apresentam os maiores preços médios dos combustíveis em 2025?

![Preço Médio por Bandeira](img/06_bandeiras_mais_caras.png)

---

# 📌 Conclusões

As análises demonstraram diferenças significativas nos preços médios dos combustíveis entre estados, produtos e bandeiras, além de permitir acompanhar a evolução dos preços ao longo do período analisado.

Todas as consultas foram executadas sobre a camada Gold, construída previamente no projeto ETL utilizando a arquitetura Medalhão (Bronze → Silver → Gold).