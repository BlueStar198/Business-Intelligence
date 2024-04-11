**Análise do Data Warehouse e Data Lake**

Este projeto aborda a geração de dados sintéticos para produtos e vendas, seguida pela criação de um data warehouse e um data lake para armazenamento e análise desses dados.

**Data Warehouse:**
- Os dados são gerados para 600 produtos e 1000 vendas, com informações como ID, nome, categoria, data da venda, quantidade vendida e valor total.
- Um data warehouse é criado combinando os dados de produtos e vendas com base no ID do produto.
- As análises realizadas incluem:
  - Análise de vendas por produto e categoria.
  - Análise de tendências temporais das vendas.
  - Análise de desempenho dos produtos.

**Data Lake:**
- São gerados dados sintéticos para simular um ambiente de data lake, com 10 arquivos CSV contendo 1000 linhas cada.
- Cada arquivo possui colunas com valores aleatórios.
- Os dados do data lake são então lidos em um banco de dados SQLite e análises são realizadas usando Pandas, Matplotlib e Seaborn.
- As análises incluem:
  - Visualização de gráficos de dispersão e histogramas.
  - Boxplot para análise da distribuição dos dados.

Para acessar o código completo e os resultados, visite o Google Colab: https://colab.research.google.com/drive/1ybiOMDzN8CNIUw1rFUoXhtXxc-vnXMey?usp=sharing
