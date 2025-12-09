# 🚀 Projeto Power BI: Análise Integrada de Contratos e Recursos Humanos

Este projeto apresenta um dashboard analítico construído no Microsoft Power BI para monitorar e analisar o desempenho de contratos de clientes e a gestão do quadro de funcionários, utilizando a **Área de Atuação** como um ponto de cruzamento chave entre as análises.

## 🎯 Objetivo
O dashboard fornece uma visão gerencial e operacional para:
1.  **Monitorar o desempenho financeiro** dos contratos, identificando contribuições por área e clientes de alto valor.
2.  **Analisar a distribuição, alocação e custo** do quadro de funcionários (salário e impostos) por nível, área e localização geográfica.
3.  **Identificar tendências** de volume de clientes e contratação ao longo do tempo.

## ⚙️ Tecnologias e Ferramentas
* **Principal:** Microsoft Power BI Desktop
* **Linguagens de Análise:** **DAX** (Data Analysis Expressions) para a criação de métricas e KPIs.
* **Transformação de Dados:** **Power Query** (M Language) para o processo de ETL (Extração, Transformação e Carregamento).

## ✨ Funcionalidades do Dashboard
O painel é interativo e permite análises dinâmicas através dos seguintes recursos:

| Funcionalidade | Descrição |
| :--- | :--- |
| **Segmentação de Dados (Slicers)** | Filtros por **Período** (Datas), **Área** (5 categorias) e **Região** (5 categorias geográficas). |
| **Cross-Filtering** | Seleção de um elemento visual (ex: uma área no gráfico) filtra automaticamente todos os demais. |
| **Visualização Geoespacial** | Utilização de um **Mapa** para visualizar a distribuição dos funcionários por Estado, com detalhamento por Nível. |
| **KPI Cards** | Destaque para métricas financeiras chave, como `Valor total contratos` (R$ 80,42 Mi) e `Salário total atual` (R$ 9,91 Mi). |

## 💡 Insights Chave Encontrados

### 💰 Análise de Contratos
* **Valor Total:** O projeto gerou **R$ 80,42 Milhões** em contratos.
* **Performance por Área:** As áreas de **Operações** (R$ 18,2 Mi) e **Financeiro** (R$ 18,3 Mi) lideram o valor total dos contratos.
* **Influência de Nível:** A maior parte dos clientes é gerida por **Coordenadores** (86 clientes) e **Diretores** (82 clientes).
* **Cliente Destaque:** O cliente **De Andrade** possui o maior valor de contrato.

### 🧑‍💼 Análise de Recursos Humanos
* **Quadro:** O total de **539 Funcionários**, com ligeira predominância de **Terceirizados** (53,25%) sobre **Efetivos** (46,75%).
* **Custo Anual:** O custo com pessoal é de **R$ 9,91 Milhões** (Salário Total Atual), mais **R$ 3,42 Milhões** em impostos.
* **Distribuição Geográfica:** Forte concentração de funcionários nas regiões **Sudeste** e **Sul** do Brasil.
* **Picos de Contratação:** Os meses de **março** e **setembro** demonstram ser os períodos de maior volume de contratações.

---



## 🌐 Visualização Online

&

## 🖥️ Como Abrir o Arquivo

1.  Garanta que você possui o **Microsoft Power BI Desktop** instalado em sua máquina.
2.  Faça o clone ou baixe o arquivo do projeto (`ProjetoPOWERBI.pbix`).
3.  Abra o arquivo `.pbix` no Power BI Desktop.
4.  *(Opcional: Se for uma base de dados externa, inclua aqui o link para o banco de dados ou CSV de origem)*
