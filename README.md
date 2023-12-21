# Projeto: Dashboard Olist

## Objetivo:
Este notebook visa realizar o tratamento e pré-processamento de dados, preparando-os para a subsequente construção de um dashboard no Power BI. Essa etapa é desenvolvida em Python, utilizando a biblioteca Pandas, devido ao seu vasto potencial de processamento de dados. A intenção é preparar os dados de forma a facilitar a exportação posterior em formato CSV. Dessa maneira, otimizamos o trabalho que teríamos no Power Query e garantimos que nosso arquivo .pbix permaneça mais leve.

## Dados:
Trata-se de uma base de dados pública do comércio eletrônico brasileiro, que registra pedidos efetuados na loja Olist. O conjunto de dados compreende informações de 100 mil pedidos realizados entre 2016 e 2018, abrangendo diversos marketplaces no Brasil. Suas características possibilitam a visualização de um pedido sob diversas perspectivas, desde o status do pedido, preço, desempenho de pagamento e frete, até a localização do cliente, atributos do produto e, por fim, avaliações redigidas pelos clientes. Adicionalmente, disponibilizamos um conjunto de dados de geolocalização que relaciona os CEPs brasileiros às coordenadas de latitude/longitude.

Os dados encontram-se disponíveis no [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).
