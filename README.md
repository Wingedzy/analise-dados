# Análise de Cancelamento de Clientes

Este projeto tem como objetivo analisar os padrões de cancelamento de clientes em uma empresa com mais de 800 mil clientes, identificando possíveis causas e propor estratégias para reduzir a taxa de churn.

---

## Objetivo

- Explorar a base de clientes para entender o comportamento de cancelamento.
- Limpar e tratar os dados para análises confiáveis.
- Gerar visualizações interativas para identificar padrões e insights.
- Obter informações que ajudem a reduzir o número de cancelamentos.

---

## Base de Dados

O dataset contém informações sobre clientes e seu status de cancelamento (`cancelou`).  

- Algumas colunas podem ter dados irrelevantes ou vazios.  
- A coluna `CustomerID` foi removida por não agregar valor à análise.  
- Linhas com dados faltantes foram descartadas.  

> Nota: O dataset utilizado é uma amostra (`cancelamentos_sample.csv`) e pode ser obtido de fontes públicas como Kaggle.

---

## Análises Realizadas

1. **Contagem de cancelamentos:**  
   - Quantos clientes cancelaram e quantos continuam ativos, em números absolutos e percentuais.  

2. **Visualização de dados:**  
   - Histogramas para cada coluna do dataset, comparando clientes que cancelaram e os que permaneceram.  
   - Uso de `Plotly Express` para gráficos interativos com valores exibidos.

---

## Ferramentas Utilizadas

- **Python** – linguagem principal  
- **Pandas** – manipulação e limpeza de dados  
- **Plotly Express** – visualizações interativas  
- **Jupyter Notebook** – desenvolvimento e apresentação do projeto

---

## Como Rodar

1. Clone o repositório:  
   ```bash
   git clone https://github.com/seu-usuario/nome-do-projeto.git
Navegue até a pasta do projeto:

bash
Copiar código
cd nome-do-projeto
Instale as dependências:

bash
Copiar código
pip install pandas plotly openpyxl nbformat ipykernel
Abra o notebook e execute as células:

bash
Copiar código
jupyter notebook
Estrutura do Repositório
csharp
Copiar código
nome-do-projeto/
│
├── data/               # Arquivo cancelamentos_sample.csv
├── notebooks/          # Notebook com análise
├── README.md           # Este arquivo
Autor
Pedro H. Mendonça
https://www.linkedin.com/in/pedrohmmwing
