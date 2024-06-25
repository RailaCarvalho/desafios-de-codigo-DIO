# 1 / 2 - Remoção de Duplicados 📊
Nível Básico <br>

## Descrição 📒
Em muitos conjuntos de dados, valores duplicados podem distorcer análises e resultados. Dada uma lista de números, você deve remover os valores duplicados e retornar uma lista com valores únicos.

### Entrada ⬅️
Uma lista de números que pode conter duplicatas. Por exemplo: ```1, 2, 2, 3, 4, 4, 5```.

### Saída ➡️
Uma nova lista contendo apenas valores únicos. Por exemplo: ```[1, 2, 3, 4, 5]```. O que fazer: Criar um conjunto a partir da lista para remover duplicatas e depois converter de volta para uma lista.

### Exemplos 📋
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis. <br>

| Entrada | Saída |
|---------|-------|
| 1, 2, 3, 4, 4, 4 | [1, 2, 3, 4] |
| 30, 31, 32, 30, 31, 31 | [32, 30, 31] |
| 1, 2, 2, 3, 4, 4, 5 | [1, 2, 3, 4, 5] |

### Explicação do Código 🖥️
- Conversão para Lista: Utilizamos int para converter os elementos da lista de strings para inteiros.

- Remoção de Duplicatas: Utilizamos a função set para criar um conjunto, o que automaticamente remove duplicatas, e depois convertemos esse conjunto de volta para uma lista.

# 2 / 2 - Contagem de Valores Nulos 📊
Nível Básico <br>

## Descrição 📒
Em análise de dados, a identificação de valores ausentes (nulos) é crucial, pois pode afetar a integridade e a qualidade dos dados. Dada uma lista de valores, você deve contar quantos desses valores são None, que representam dados ausentes.

### Entrada ⬅️
Uma lista de valores númericos positivos e valores None. Por exemplo: ```1, None, 2, None, 3, None``` .

### Saída ➡️
Um número inteiro que indica quantos valores nulos estão presentes na lista. Por exemplo: ```3```. O que fazer: Conte quantos elementos são None usando a função count do Python.

### Exemplos 📋
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada | Saída |
|---------|-------|
| 1, 2, None, 5, 6 | 1 |
| 10, 15, None, 20, 40 None, 1 | 2 |
| None, None, None, None, None | 5 |

### Explicação do Código 🖥️
- Entrada dos Dados: Usamos ```input``` para receber a lista e ```split``` para separá-la em elementos individuais, removendo espaços em branco com ```strip```.

- Conversão para Lista: Utilizamos ```split``` para separar a string em elementos. Usamos ```strip``` e ```isdigit``` para converter números para ```int``` e substituímos não-números por ```None```.

- Contagem de Nulos: Podemos contar quantos elementos são None usando a função ```count```.
