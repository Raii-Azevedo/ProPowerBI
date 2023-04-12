## O que é o PowerBI?
 - PowerBI é uma ferramenta de Business Intelligence. Ou seja, é um ferramenta de apoio a decisão que visa a gestão de performance e oportunidades de negócios.
  
  ### O que é possível fazer com o BI:
  - Trabalhar/manipular os dados
  - Transformar informações
  - Gerar conhecimento
  - Visualização de Dados
  - Apoio a tomada de decição
  - Apoio na visualização de oportunidades

  ### Qual o foco do Business Intelligence?
    - Prover o acesso
    - Apresentação de informação
    - Objetivos estratégicos
    - Identificar oportunidades de negócio

  
## O que é ETL?
- Extract Transform Load (Extração Transformação Carga) ETL busca trabalhar com a extração de dados de origem (fonte) externa.
  - ARQUITETURA:
    - Extração (Coleta de dados)
    - Limpeza e Ajuste (Melhorar a qualidade dos dados)
    - Entrega ou Carga de Dados (Estrutura visual)
    - Gerenciamento (planos de backup, itens de segurança, automatização)
  
  - REQUISITOS para ETL
    - Requisitos do negócio
    - Viabilidade dos Dados
    - Latência dos dados 
    - Políticas de Compliance e Segurança

## O que é DW e DM?
- DataWarehouse: É a fonte(repositório) que irá alimentar a visualização de dados.
  
### Para que serve?
  - Para criar uma visão única e centralizada dos dados que anteriormente estavam dispersos.
  - É orientado ao assunto (criado para facilitar o entendimento e visualização dos dados)

## Tabelas Fato e Dimensão
 - Tabela Fato: Armazena os valores detalhados das medidas ou fatos (O que aconteceu: Venda, contratação, Quantidade, valor de um produto...).
 - Tabela Dimensão: Contém o nome específico de cada produto, Ou seja, define-se uma ID - Seguido de nome para especifícação.

## O que é Star Schema e Snow Flake?
  - Star Schema: O modelo mais utilizado na modelagem dimensional. O esquema estrela é composto por uma tabela fato ao centro, rodeado de tabelas dimensão.
  - Snow Flake: O Snowflake não coloca limites rígidos no número de bancos de dados, esquemas (dentro de um banco de dados) ou objetos (dentro de um esquema.