# Primeira Aula de Power BI: Criando um meu primero Dashboard

## Introdução

Bem-vindo ao meu primeiro projeto prático de Power BI! Estou compartilhando a minha primeira experiência criando um dashboard financeiro a partir de um conjunto de dados fictício. Este dashboard oferece insights sobre o desempenho financeiro da empresa, incluindo faturamento, produtos mais vendidos, desempenho de clientes e marcas, além da distribuição geográfica das vendas.

## Objetivo

O objetivo desta aula é aprender a:

1. Importar dados para o Power BI.
2. Criar visualizações interativas.
3. Montar um dashboard consolidado.
4. Interpretar os insights obtidos a partir das visualizações.

## Passo a Passo para Criar o Dashboard

### Importar e Transformação dos Dados
- **Passos de Transformação:**
  - **Remoção de dados nulos:** As colunas e linhas nulas foram removidas da base de dados.
  - **Alteração dos tipos de dados:** Após verificação observou-se que os tipos de dados não correspondiam com o desejado e assim, foi-se feita a alteração.
  - **Dividisão de Colunas:** A coluna `Localidade` da base de dados estava em formato: `País - Continente`. Utilizando da funcionalidade `Dividir coluna por delimitador` a mesma foi separada em duas colunas compatíveis com seus respectivos dados.
  - **Transformação de coluna:** Os dados da coluna `Nome` estavam em formato `Sobrenome.'Nome`, utilizando a funcionalidade `Coluna de exemplo` a mesma foi alterada para o formato: `Nome Sobrenome.`.  
  - **Criação de nova coluna:** A partir da multiplicação das colunas `Preço Unitário` e `Qtd. Vendida` foi criada uma nova coluna: `Faturamento`.

## Interpretação dos Insights

## Dashboard
![Painel de Análise de Vendas](arquivos/Aula%201.png)

### Faturamento Total
- **Insight**: O faturamento total de R$ 64,17 milhões indica um bom desempenho financeiro.

### Produto Mais Vendido
- **Insight**: O DVD M360 Preto é o produto líder em vendas, crucial para estratégias de marketing e estoque.

### Quantidade Vendida por Nome Cliente
- **Insight**: Taylor W. é o cliente que mais compra, seguido por Bruce S. e Jon Y., sugerindo uma base de clientes fiéis.

### Faturamento por País
- **Insight**: A empresa possui uma presença internacional significativa, com fortes vendas na América do Norte, Europa e Ásia.

### Quantidade Vendida por Marca
- **Insight**: Hashtag Toys é a marca mais vendida, seguida por Southridge, destacando preferências de marca entre os clientes.

### Faturamento e Quantidade Vendida por Ano e Mês
- **Insight**: A sazonalidade é evidente com picos notáveis em novembro, possivelmente devido a promoções de fim de ano.

## Considerações sobre a Base de Dados

A base de dados utilizada contém as seguintes colunas: 

- **Data da Venda**: Data em que a venda foi realizada.
- **Produto**: Nome do produto vendido.
- **Categoria**: Categoria do produto (ex: Sistema de Som, Ventiladores).
- **Preço Unitário**: Preço por unidade do produto.
- **Custo Unitário**: Custo por unidade do produto.
- **Marca**: Marca do produto.
- **Qtd. Vendida**: Número de unidades vendidas.
- **Nome Cliente**: Nome do cliente que realizou a compra.
