# Super Trunfo de Países

## Sobre o Projeto

Este projeto em C simula cartas do jogo Super Trunfo com informações sobre cidades brasileiras. Cada carta contém dados como estado, código, nome da cidade, população, área, PIB, número de pontos turísticos, além de atributos calculados: densidade populacional e PIB per capita.

---

## Funcionalidades

### Nível 1: Cadastro das Cartas

- Permite o cadastro de duas cartas com os seguintes dados:
  - Estado (A-H)
  - Código da carta (ex: A01)
  - Nome da cidade
  - População
  - Área (km²)
  - PIB (bilhões de reais)
  - Número de pontos turísticos
- Exibe os dados cadastrados de forma organizada.

### Nível Novato: Comparação de Cartas

- Calcula os atributos:
  - Densidade populacional = população / área
  - PIB per capita = PIB / população
- Compara duas cartas com base em um atributo numérico escolhido no código:
  - População
  - Área
  - PIB
  - Densidade populacional
  - PIB per capita
- Regras de comparação:
  - Para todos os atributos, exceto densidade populacional, vence o maior valor.
  - Para densidade populacional, vence o menor valor.
- Exibe o resultado da comparação, indicando a carta vencedora e os valores comparados.

---

## Como Usar

1. Compile o código:
   ```bash
   gcc super_trunfo.c -o super_trunfo
