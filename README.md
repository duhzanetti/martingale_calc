# Simulador de Martingale

Este é um simulador para operações de opções binárias utilizando a estratégia de Martingale. O objetivo da página é calcular as perdas e ganhos em uma série de entradas, levando em conta o saldo inicial, valor da entrada inicial, fator de multiplicação de Martingale e o payout. A tabela gerada exibe as informações de forma clara e facilita o acompanhamento do desempenho das operações.

## Funcionalidades
- Inserir saldo inicial
- Definir o valor da primeira entrada
- Especificar o fator de multiplicação de Martingale
- Inserir o payout (percentual de retorno)
- Gerar automaticamente uma tabela com os cálculos de entradas, perdas e lucros

## Colunas exibidas na tabela
1. **Nº da entrada (Nº)**: Número sequencial de cada entrada.
2. **Valor da entrada (VALOR)**: O valor investido na respectiva entrada.
3. **Perca (PERCA)**: A soma acumulativa das perdas das entradas anteriores.
4. **Lucro (LUCRO)**: O valor de lucro obtido na entrada atual, com base no payout definido.
5. **Balanço (BALANÇO)**: O lucro líquido após subtrair a perda acumulada da linha anterior.

## Instalação como App
Esta página pode ser instalada como um aplicativo no navegador Microsoft Edge, seguindo as diretrizes de Progressive Web App (PWA).

## Como usar
- Acesse a página.
- Insira os valores conforme sua estratégia.
- Visualize os resultados gerados na tabela para acompanhamento.
