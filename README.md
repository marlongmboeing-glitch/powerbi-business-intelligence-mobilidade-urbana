markdown# 📊 Business Intelligence Aplicado à Mobilidade Urbana
## Análise Estratégica para Maximização do Retorno Financeiro por Quilômetro Rodado

Este projeto representa a evolução de análises desenvolvidas anteriormente em Excel e SQL. Utiliza o **Power BI** para transformar dados operacionais em informações estratégicas, apoiando a tomada de decisão baseada em dados.

---

## 🎯 Objetivo

Identificar padrões de mobilidade urbana e oportunidades para maximizar o retorno financeiro por quilômetro rodado, considerando:
* Demanda por região
* Ticket médio
* Perfil das corridas
* Posicionamento regional
* Eficiência operacional

---

## ❓ Problema de Negócio

> Como maximizar o retorno financeiro por quilômetro rodado utilizando dados de mobilidade urbana, demanda regional, ticket médio e perfil das corridas para apoiar decisões operacionais de motoristas por aplicativo?

---

## 🛠 Ferramentas Utilizadas

* **Power BI** (Visualização e Dashboards)
* **Power Query** (ETL e Tratamento de Dados)
* **Modelagem Dimensional** (Arquitetura de Dados)
* **DAX** (Cálculo de Métricas e KPIs)

---

## 📈 Principais Análises

* **Temporal**: Corridas por data e por hora.
* **Geográfica**: Corridas, faturamento e ticket médio por Regional.
* **Perfil**: Corridas por faixa de distância.
* **Demanda**: Destinos com maior concentração de corridas.

---

## 💡 Principais Insights

A análise demonstrou que a maximização do retorno financeiro **não depende exclusivamente** do maior ticket médio. Os resultados sugerem que a concentração operacional em regiões próximas à residência do motorista tende a proporcionar:
* Maior frequência de corridas
* Redução do tempo ocioso
* Menor deslocamento vazio
* Menor depreciação do veículo
* Melhor aproveitamento financeiro por quilômetro rodado

---

## 📌 Metodologia

O projeto foi desenvolvido utilizando **Modelagem Dimensional**, relacionando tabelas fato e dimensão para a construção de indicadores estratégicos por meio de medidas DAX. 

> ⚠️ **Nota:** A análise foi realizada sobre uma amostra de corridas de Curitiba. O objetivo é identificar padrões operacionais e apoiar a tomada de decisão, sem generalizar compulsoriamente os resultados para toda a cidade.

---

## 🗂 Modelagem de Dados

### Tabela Fato (`fato_corridas`)
* `bairro_origem`
* `bairro_destino`
* `data`
* `hora`
* `valor_corrida`
* `distancia_km`
* `faixa_distancia`

### Dimensão Tempo (`dim_tempo`)
* `Data` / `Hora`
* `Período` / `Faixa Horária`

### Dimensão Bairro (`dim_bairro`)
* `Bairro`
* `Regional`

---

## 📊 Indicadores (KPIs)

* **Corridas Totais** (`COUNT`)
* **Faturamento Total** (`SUM`)
* **Ticket Médio** (`AVERAGE`)

---

## 🚀 Competências Demonstradas

* Business Intelligence & Analytics
* Modelagem de Dados Dimensional (Star Schema)
* Data Storytelling
* Tomada de Decisão Baseada em Dados

---

## 📷 Dashboard

*Aqui você pode inserir o print do seu painel do Power BI:*
![Dashboard de Mobilidade Urbana](SUA_URL_DA_IMAGEM_AQUI.png)

> **Visualizações Inclusas:** Distribuição de corridas totais por Regional, análise temporal por hora e cruzamento estratégico das Regionais de Curitiba.

---

## 📂 Portfólio

Este projeto integra meu portfólio pessoal de **Business Analytics**, demonstrando maturidade técnica na resolução de problemas reais de negócio através da transição entre Excel, SQL e Power BI.
