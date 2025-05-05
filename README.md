📦 Regressão com Random Forest em Dados de E-commerce
Este projeto demonstra a aplicação de um modelo de Regressão com Random Forest para prever o valor total das vendas (Sales_Amount) em um dataset de transações de e-commerce.

🧠 Objetivo
Construir um modelo preditivo que estime o valor de venda de cada transação com base em variáveis como quantidade, preço unitário, produto, país e cliente. Isso permite análises mais profundas de comportamento de consumo e previsão de receita.

🔧 Tecnologias e Bibliotecas
Python 3, Pandas, Scikit-learn, Matplotlib e Seaborn (visualização)

📊 Dataset
O dataset contém colunas típicas de um sistema de vendas, como:
* InvoiceNo: Número da fatura
* StockCode: Código do produto
* Description: Descrição do produto
* Quantity: Quantidade vendida
* UnitPrice: Preço unitário
* CustomerID: ID do cliente
* Country: País de origem
* InvoiceDate: Data da venda

A base foi pré-processada com limpeza de dados, transformação de data e criação de novas variáveis.

🔄 Etapas do Projeto
1. Carregamento dos dados
2 e 3. Análise Exploratória/Estatística báasica
4. Aplicação do algoritmo de Machine Learning
5. Avaliação com Mean Squared Error (MSE)

📈 Resultados Esperados
- Com o modelo treinado, é possível:
- Prever valores de faturamento com base nas variáveis de entrada
- Compreender a influência de fatores como produto, país e cliente no volume de vendas

💡 Possíveis Melhorias Futuras
- Inclusão de variáveis temporais (ex: sazonalidade)
- Ajuste fino de hiperparâmetros via GridSearchCV
- Visualização de importância das variáveis do modelo
