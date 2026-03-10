Análise de Churn - TelecomX 📊
Este projeto faz parte de um desafio de Ciência de Dados focado em identificar padrões de evasão de clientes em uma empresa de telecomunicações. O objetivo é transformar dados brutos de uma API em insights estratégicos para retenção.

🛠️ O que foi feito
O projeto seguiu as etapas principais de um pipeline de dados:

Extração e Normalização: Leitura de arquivos JSON aninhados e transformação em um DataFrame Pandas estruturado.

Limpeza de Dados: Tratamento de valores nulos, conversão de tipos (strings para numéricos) e remoção de inconsistências.

Engenharia de Variáveis: Criação de métricas personalizadas (como Gastos Diários) utilizando NumPy para otimizar os cálculos.

Análise Exploratória (EDA): Visualização de dados com Matplotlib e Seaborn para cruzar variáveis demográficas e financeiras com a taxa de cancelamento.

📈 Principais Insights
Contratos: Clientes com contratos mensais são os que mais saem.

Tempo de Casa: O risco de evasão é crítico nos primeiros meses de assinatura.

Serviços: Clientes de fibra óptica possuem uma taxa de churn acima da média.

Financeiro: Faturas mensais mais altas estão diretamente ligadas a uma maior probabilidade de cancelamento.

🚀 Tecnologias Utilizadas
Python 3

Pandas: Manipulação e tratamento.

NumPy: Cálculos matemáticos.

Matplotlib & Seaborn: Visualização de dados.
