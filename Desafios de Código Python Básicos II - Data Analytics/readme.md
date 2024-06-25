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
