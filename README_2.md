# TesteDeveloper - Controle de Estoque

## Sobre o projeto

Aplicação desenvolvida em C# com .NET 8 para controle e consulta de estoque.

O objetivo do projeto é trabalhar com produtos identificados por referência,
controlando o saldo disponível e verificando se existe quantidade suficiente
para atender uma solicitação.

## Tecnologias utilizadas

- C#
- .NET 8
- Visual Studio 2022

## Funcionalidades

- Cadastro de produtos em memória
- Consulta de saldo por referência
- Verificação de disponibilidade de estoque
- Comparação de produtos através da referência

## Estrutura

### EstoqueProduto

Classe responsável por representar um produto no estoque.

Possui:
- Referência do produto
- Saldo disponível

A comparação dos produtos utiliza a referência como identificador.

## Como executar

1. Clone o repositório
2. Abra o projeto no Visual Studio
3. Execute a aplicação