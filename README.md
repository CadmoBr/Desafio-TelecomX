# Desafio-TelecomX
Este projeto tem como objetivo analisar a evasão de clientes (churn) em uma empresa de telecomunicações, identificando padrões e fatores associados ao cancelamento de serviços. A análise foi realizada utilizando Python e bibliotecas como Pandas, NumPy, Matplotlib e Seaborn.

📦 Sobre o Projeto
A evasão de clientes é um dos principais desafios enfrentados por empresas de serviços recorrentes. Antecipar quais clientes têm maior propensão a cancelar permite criar estratégias de retenção mais eficazes.

Neste notebook, realizei:

Extração dos dados de um dataset público.
Limpeza, transformação e preparação dos dados.
Análises estatísticas e visuais para identificar padrões de churn.
Geração de insights e recomendações estratégicas.
🔗 Fonte dos Dados
Os dados utilizados estão disponíveis em:
TelecomX_Data.json

⚙️ Etapas do Projeto
1. Extração
Importação dos dados diretamente de um arquivo JSON hospedado no GitHub.
Conversão para DataFrame Pandas.
2. Transformação
Verificação e tratamento de valores ausentes.
Conversão de colunas binárias (Yes/No) para valores numéricos (0/1).
Ajuste dos tipos de dados para facilitar análises.
Renomeação de variáveis e rótulos para melhor visualização.
3. Análise
Estatísticas descritivas por grupo de churn.
Visualização da distribuição de churn (gráficos de barras).
Análise de churn por variáveis categóricas (contrato, método de pagamento, dependentes, etc.).
Análise de churn por variáveis numéricas (tempo de contrato, gastos mensais e totais).

📊 Principais Resultados
Clientes com contrato mensal possuem maior taxa de cancelamento.
Planos com cobrança mais alta estão mais relacionados com churn.
Curto tempo de permanência (tenure) está fortemente relacionado com churn.
Tipo de contrato: Contratos mensais apresentaram maior evasão; contratos de 1 ou 2 anos mostraram maior fidelidade.
Método de pagamento: Cheque eletrônico está associado a maior churn; métodos automáticos têm menor evasão.
Perfil de clientes: Clientes sem dependentes ou parceiros e com pouco tempo de contrato são mais propensos a cancelar.
Gasto total: Clientes que cancelaram tinham, em média, menor gasto total e menor tempo de contrato.

💡 Insights e Recomendações
Fidelização: Incentivar contratos anuais ou bianuais com descontos.
Alerta de churn: Monitorar clientes com baixa tenure e cobrança mensal elevada.
Programas de retenção: Oferecer benefícios a clientes novos nos primeiros 6 meses.

🛠️ Como Executar
Clone este repositório.
Instale as dependências:
pip install pandas numpy matplotlib seaborn requests
