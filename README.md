# Segundo desafio do Felipão 
Desafio proposto pelo Felipão da DIO: Calculadora de Partidas Rankeadas.


A função `calculadora` recebe o número de vitórias e derrotas de um herói e determina seu nível com base em faixas específicas de vitórias. O código utiliza uma estrutura de switch para realizar essa classificação. Aqui estão os principais pontos:

## Função Calculadora
- A função recebe os parâmetros `vitorias` e `derrotas`.
- Utiliza um switch para avaliar o número de vitórias e atribuir um nível correspondente.
- Retorna um objeto contendo o saldo (diferença entre vitórias e derrotas) e o nível do herói.

## Classificação por Vitórias
- O herói é classificado em diferentes níveis com base no número de vitórias.
- Os níveis incluem Ferro, Bronze, Prata, Ouro, Diamante, Lendário, e Imortal.
- Caso o número de vitórias não esteja em nenhuma faixa especificada, o nível é definido como "Classificação não encontrada".

## Exemplo de Uso
- Chama a função `calculadora` com um exemplo de 80 vitórias e 10 derrotas.
- O resultado é armazenado na variável `resultado`.
- Exibe o saldo e o nível do herói utilizando um `console.log`.

## Saída
- Imprime a mensagem: "O Herói tem um saldo de {saldo} e está no nível de {nível}".

---

*Este código fornece uma função simples para calcular o nível de um herói com base em suas vitórias, demonstrando a utilização de estruturas de controle em JavaScript.*

