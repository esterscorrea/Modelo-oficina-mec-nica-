# Modelo Conceitual – Oficina Mecânica

Este repositório contém o modelo conceitual de um sistema de controle e
gerenciamento de ordens de serviço de uma oficina mecânica, desenvolvido
com base em uma narrativa proposta no desafio.

## Contexto

Clientes levam veículos à oficina para consertos ou revisões periódicas.
Cada veículo gera ordens de serviço associadas a equipes de mecânicos,
serviços executados e peças utilizadas. O valor total da OS é calculado
a partir da soma dos serviços (mão de obra) e das peças aplicadas.

## Modelo Conceitual

![Diagrama Conceitual](diagrama_oficina.png)

## Observações

Os relacionamentos muitos-para-muitos entre Ordem de Serviço e
Serviço/Peça foram resolvidos por meio de entidades associativas,
permitindo o controle de quantidades e valores individuais.
