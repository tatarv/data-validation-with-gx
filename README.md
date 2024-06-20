# Introdução

Esse projeto foi criado visando implementar testes de qualidade de dados com a ferramenta Great Expectations

# Objetivo

Explorar mais a ferramenta e aprender na prática como utilizar para validações de dados

# Great Expectations

O Great Expectations é um framework de validação de dados de código aberto desenvolvido em Python. 
Ele permite que engenheiros e cientistas de dados codifiquem, documentem e validem expectativas em relação aos seus conjuntos de dados, 
automatizando e reforçando o processo de garantia de qualidade dos dados.

# Regras para validações no dataset

Para esse projeto foi utilizado como dataset um arquivo csv com dados de usuários em um sistema contendo Nome, Matrícula, E-mail e Telefone.
Para criar validações considere o seguinte:

- Dataset deve conter os campos: Nome, Matrícula, E-mail e Telefone
- Todos os campos devem ser do tipo string
- Os campos Nome, Matrícula e E-mail são obrigatórios
- Os campos Matrícula e E-mail não devem ter valores repetidos

# Expectations para as validações

- expect_column_to_exist: Verifica se uma coluna existe.
- expect_column_values_to_be_of_type: Verifica se os valores de uma coluna são de um tipo específico.
- expect_column_values_to_not_be_null: Verifica se os valores de uma coluna não são nulos.
- expect_column_values_to_be_unique: Verifica se todos os valores de uma coluna são únicos.

# Documentação da ferramenta

https://docs.greatexpectations.io/docs/reference/learn/terms/data_docs/