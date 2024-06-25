# 1 / 2 - Cálculo de Média 📊
Nível Básico <br>

## Descrição 📒
Calcular a média é uma das operações estatísticas mais básicas e úteis para resumir um conjunto de dados. Dada uma lista de números, você deve calcular a média aritmética desses números.

### Entrada ⬅️
Uma lista de números. Por exemplo: ```10, 20, 30, 40, 50```

### Saída ➡️
Um número representando a média dos números na lista. Por exemplo: ``` 30.0 ```. O que fazer: Somar todos os números e dividir pela quantidade de elementos na lista.

### Exemplos 📋
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis. <br>

| Entrada | Saída |
|---------|-------|
| 8.8, 5.0, 7.5 | 7.1 |
| 3.2, 7.0, 9.0 | 6.4 |
| 10, 20, 30, 40, 50 | 30.0 |

### Explicação do Código 🖥️

- Conversão para Lista: Utilizamos float para converter os elementos da lista de strings para números de ponto flutuante.

- Cálculo da Soma: Utilizamos a função sum para calcular a soma de todos os números na lista.

- Cálculo da Quantidade: Utilizamos len para calcular o número de elementos na lista.

- Cálculo da Média: Dividimos a soma pela quantidade de elementos para obter a média.

# 2 / 2 - Cálculo de Mediana 📊
Nível Básico <br>

## Descrição 📒
A mediana é uma medida de tendência central que é menos sensível a valores extremos do que a média. Dada uma lista de números, você deve calcular a mediana.

### Entrada ⬅️
Uma lista de números (por exemplo: ```10, 20, 30, 40, 50```).

### Saída ➡️
Um número representando a mediana (por exemplo: ```30.0```). O que fazer: Ordenar a lista e encontrar o valor do meio (ou a média dos dois valores do meio se a lista tiver um número par de elementos).

### Exemplos 📋
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada | Saída |
|---------|-------|
| 10, 20, 30, 40, 50 | 30.0 |
| 2, 4, 6, 8, 10 | 6.0 |
| 8, 4, 5, 6, 2, 1 | 4.5 |

