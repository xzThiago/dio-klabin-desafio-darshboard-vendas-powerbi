# Projeto: Relatório de Análise Financeira (Power BI)

Este projeto consiste em um dashboard interativo desenvolvido no Microsoft Power BI para analisar o desempenho de vendas de uma empresa. O relatório oferece uma visão consolidada dos principais indicadores financeiros, permitindo a filtragem e a exploração dos dados por diferentes dimensões.

A base de dados utilizada é a amostra (sample) **"Financials"** fornecida pela Microsoft, que contém dados fictícios de vendas, incluindo segmentos de mercado, produtos, países, e métricas financeiras.

## Preview do Dashboard

![Preview do Relatório de Vendas](<img width="1331" height="768" alt="image" src="https://github.com/user-attachments/assets/5466c5c7-32f5-4f8a-8607-125ef4426efe" />
)

## 🎯 Objetivo

O principal objetivo deste dashboard é fornecer insights rápidos e claros sobre o desempenho das vendas, permitindo que gestores e analistas:
* Monitorem a receita e o lucro total.
* Identifiquem quais produtos, segmentos e países estão impulsionando o crescimento.
* Analisem tendências de vendas ao longo do tempo (sazonalidade).
* Compreendam a relação entre unidades vendidas e o preço médio de venda.

## 🛠️ Ferramentas Utilizadas

* **Microsoft Power BI Desktop:** Ferramenta principal para importação, modelagem de dados, criação de cálculos (DAX) e desenvolvimento das visualizações.
* **DAX (Data Analysis Expressions):** Utilizado para criar as métricas centrais, como `Total Revenue`, `Total Profit`, `Soma de Discounts`, etc.

## 📊 Componentes do Relatório

O dashboard é composto por uma página principal que resume o desempenho das vendas através dos seguintes elementos:

### 1. Indicadores Chave de Desempenho (KPIs)

Cartões que exibem as métricas mais importantes de forma clara e direta:
* **Total Revenue (Receita Total):** O faturamento total gerado.
* **Soma de Discounts (Soma de Descontos):** O valor total concedido em descontos.
* **Sales Quantity (Quantidade de Vendas):** O número total de transações ou registros de vendas.
* **Total Profit (Lucro Total):** O lucro líquido obtido.

### 2. Filtros Interativos (Slicers)

Permitem ao usuário segmentar os dados de todo o relatório com base em:
* **Ano:** Filtragem por período (ex: 2013, 2014).
* **Segment (Segmento):** Filtro por segmento de mercado (ex: Government, Midmarket, Enterprise).
* **Product (Produto):** Filtro por linha de produto (ex: Paseo, Velo, Montana).

### 3. Visualizações de Dados

* **Total Sales by Product (Vendas Totais por Produto):**
    * **Tipo:** Gráfico de barras horizontais.
    * **Função:** Compara o desempenho de receita entre os diferentes produtos, facilitando a identificação dos mais vendidos.

* **Total Sales by Country (Vendas Totais por País):**
    * **Tipo:** Gráfico de colunas.
    * **Função:** Mostra a distribuição geográfica da receita, destacando os principais mercados.

* **Total Sales by Month (Vendas Totais por Mês):**
    * **Tipo:** Gráfico de área.
    * **Função:** Ilustra a tendência e a sazonalidade das vendas ao longo dos meses.

* **Detalhes de Vendas (Tabela):**
    * **Tipo:** Matriz (Tabela).
    * **Função:** Fornece um detalhamento granular por produto, mostrando `Units Sold` (Unidades Vendidas) e `Average Selling Price` (Preço Médio de Venda).

## 🚀 Como Utilizar

1.  **Visão Geral:** Observe os KPIs principais para ter um entendimento imediato da saúde financeira.
2.  **Filtragem:** Utilize os filtros de Ano, Segmento ou Produto no painel esquerdo para focar sua análise.
3.  **Análise Detalhada:** Explore os gráficos para entender *quais* produtos e países estão contribuindo para os resultados.
4.  **Tendências:** Use o gráfico de "Vendas por Mês" para identificar padrões sazonais.
