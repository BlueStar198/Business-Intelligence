**Introdução ao Projeto**

Este projeto apresenta uma série de códigos que demonstram diferentes processo de análise de dados, desde a extração até a visualização e armazenamento dos resultados. Dividido em duas partes, o projeto aborda a criação do processo ETL (Extract, Transform, Load) e Data Warehouse.

**ETL (Extract, Transform, Load):**
Na primeira parte, são apresentados códigos que demonstram o processo de extração, transformação e carregamento de dados de vendas de duas filiais distintas. A extração é realizada a partir de arquivos CSV e Excel, seguida pela aplicação de transformações nos dados, como o cálculo do valor total das vendas. Os dados transformados são então carregados em um banco de dados SQLite, onde são disponibilizados para análise por meio de consultas SQL.

Este código demonstra um processo ETL básico, envolvendo a extração de dados de vendas de filial1 e filial2, a realização de transformações nos dados e o carregamento desses dados em diferentes destinos.

**Extração:**
- Os dados de vendas da filial 1 são extraídos de um arquivo CSV.
- Os dados de vendas da filial 2 são extraídos de um arquivo Excel.

**Transformação:**
- As transformações incluem o cálculo do valor total de vendas para cada filial, multiplicando a quantidade vendida pelo preço unitário.
- Os dados transformados são visualizados e depois salvos em arquivos CSV.

**Load (Carregamento):**
- Os dados transformados são carregados em um banco de dados SQLite, tanto diretamente dos DataFrames quanto por meio de consultas SQL.

**Resultados:**
- Dados extraidos dos dados de vendas filial1 e filial2:

  ![image](https://github.com/BlueStar198/Business-Intelligence/assets/41968462/414e728c-04b1-4ca2-946a-48eec9a68380)

- Transformacao dos dados para calcular o valor total de vendas para cada filial:

  ![image](https://github.com/BlueStar198/Business-Intelligence/assets/41968462/62e40bb8-6e0e-4efe-941d-caecde54f5a0)

- Dados transformados para um arquivo CSV:

  ![image](https://github.com/BlueStar198/Business-Intelligence/assets/41968462/6bc53eba-db7f-412d-a7c3-d1966c088428)

- Dados transformados para as tabelas SQL:

  ![image](https://github.com/BlueStar198/Business-Intelligence/assets/41968462/57d60a18-854a-4694-9565-9b048c409b84)

- Carregamento dos dados transformados na tabela SQL:

  ![image](https://github.com/BlueStar198/Business-Intelligence/assets/41968462/0d9dbfc2-93e7-449d-befd-fabc6890298f)


  
**Data Warehouse:**
Na segunda parte mostra a geração de dados dos produtos e vendas, seguida pela integração desses dados em um Data Warehouse. São realizadas análises detalhadas sobre as vendas de produtos, incluindo tendências temporais, desempenho por produto e categoria, além de visualizações gráficas para facilitar a compreensão dos dados.

**Resultados:**
- No codigo são gerados os dados de 600 produtos e 1000 vendas, com informações como ID, nome, categoria, data da venda, quantidade vendida e valor total.
- Um data warehouse é criado combinando os dados de produtos e vendas com base no ID do produto:
  ![image](https://github.com/BlueStar198/Business-Intelligence/assets/41968462/c7e8f539-f824-47ff-bc2e-70cd538b727d)

- No codigo gera as análises realizadas que incluem:
  - Análise de vendas por produto e categoria.
  - Análise de tendências temporais das vendas.
  - Análise de desempenho dos produtos.
  - Grafico sobre as analises acimas.
![image](https://github.com/BlueStar198/Business-Intelligence/assets/41968462/c0abc64f-1f03-4115-887b-f6dd81a35a6e)


**Data Lake:**
Este código da Data Lake gera 10 arquivos CSV dentro dele, cada um contendo dados aleatórios com três colunas. Os dados incluem números inteiros, números reais e valores de categoria. Após a geração dos dados, ele confirma o sucesso e mostra 10 registros de cada arquivo CSV.

**Resultados:**
- São gerados dados sintéticos para simular um ambiente de data lake, com 10 arquivos CSV contendo 1000 linhas cada.
- Cada arquivo possui colunas com valores aleatórios.

![image](https://github.com/BlueStar198/Business-Intelligence/assets/41968462/df0d0dac-491f-4c6a-8e9b-fbf9cc861997)

- Os dados do data lake são então lidos em um banco de dados SQLite e análises são realizadas usando Pandas, Matplotlib e Seaborn.
- As análises incluem:
  - Visualização de gráficos de dispersão e histogramas.
  - Boxplot para análise da distribuição dos dados.
  /// POR CAUSA DE ERRO NO CODIGO ESTA SEM IMAGEM DO RESULTADO//////

Para acessar o código completo e os resultados, visite o Google Colab: https://colab.research.google.com/drive/1ybiOMDzN8CNIUw1rFUoXhtXxc-vnXMey?usp=sharing
