# Projeto ETL e Análise de Churn - TelecomX

Este projeto aplica técnicas de ETL (Extract, Transform, Load) e Análise Exploratória de Dados em um dataset de telecomunicações. O objetivo principal é identificar os fatores que levam os clientes a cancelarem seus serviços (Churn).

## 🚀 Etapas do Projeto

### 1. Extração e Tratamento (Pandas I/O & Transformação)
- Ingestão de dados diretamente de uma API via URL.
- **Normalização de JSON**: Expansão de dicionários aninhados em colunas individuais.
- **Limpeza**: Conversão de tipos de dados (strings para numéricos) e tratamento de valores nulos e vazios.
- **Codificação**: Transformação de variáveis categóricas (Sim/Não) em binárias (1/0) para análise estatística.

### 2. Análise Numérica (NumPy)
- Utilização do **NumPy** para cálculos eficientes.
- Criação da métrica `Contas_Diarias`, calculando o gasto proporcional por dia de serviço.

### 3. Visualização de Dados (Matplotlib & Seaborn)
- Análise da distribuição da variável alvo (Churn).
- Cruzamento de dados categóricos (Contratos, Métodos de Pagamento, Serviços).
- Análise de variáveis numéricas (Tenure e Monthly Charges) para identificar padrões de comportamento.

## 📊 Principais Insights
- **Retenção inicial:** Clientes com menos de 6 meses de casa possuem a maior taxa de evasão.
- **Tipo de Contrato:** Planos mensais (Month-to-month) são os principais responsáveis pelo Churn.
- **Custo:** Clientes que cancelam geralmente possuem faturas mensais mais elevadas que a média da base.

## 🛠️ Tecnologias
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📂 Como executar
1. Instale as dependências: `pip install pandas numpy matplotlib seaborn`
2. Execute o notebook `desafio_telecom.ipynb`
