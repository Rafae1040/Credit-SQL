# Exploração e Análise de Dados de Crédito com SQL


## Introdução:

Este projeto tem como objetivo analisar dados de clientes bancários, utilizando a linguagem SQL no ambiente AWS Athena. A tabela "credito" contém informações vitais, incluindo idade, sexo, dependentes, escolaridade, salário anual, tipo de cartão e métricas transacionais. A exploração detalhada destes dados proporcionará insights valiosos para estratégias de negócios.

## Metodologia:

Exploração de Dados:

Determinação da quantidade total de registros na base.
Identificação de características nulas e descrição detalhada das colunas.
Análise de valores distintos para compreensão dos tipos de dados presentes.

Análise de Dados:

Faixa Salarial: 
Identificação das faixas salariais predominantes e casos sem informação.
Sugestão de estratégias para atender clientes de menor renda.


Distribuição por Gênero:

Contagem e visualização da proporção entre clientes masculinos e femininos.

Características dos Maiores Gastos:

Identificação do cliente com a maior quantidade de transações.
Recomendação de oferecer maior limite a clientes com comportamento transacional expressivo.


Comparação de Gastos entre Gêneros:

Análise da similaridade nos gastos entre homens e mulheres.


Características dos Compradores de Produtos:

Exame dos clientes que compram mais produtos, com foco na faixa salarial.


## Ferramentas Utilizadas:

SQL: Consultas realizadas no AWS Athena.

Armazenamento: Utilização de S3 Bucket para armazenar a versão dos dados disponíveis no link do GitHub.


# Conclusão:

Essas foram algumas análises extraídas do dataset de crédito.

Alguns insights interessantes:

1. A maior parte dos clientes possui renda até 40K
2. Os clientes com maiores limites são em sua maioria homens e divorciados
3. Os clientes com menores limites são em sua maioria mulheres e solteiras
4. Os clientes com menores transacoes os que usam cartão platinum
5. O limite de crédito é diretamente afetado pela faixa salarial do cliente.
6. Não há clientes do sexo feminino com renda anual acima de 60 mil.

