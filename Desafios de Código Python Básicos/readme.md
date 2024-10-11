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

# 1 / 3 - Verificador de Planos de Internet 📊
Nível Básico <br>

## Descrição 📒
Uma empresa de telecomunicações deseja criar uma solução algorítmica que ajude aos seus clientes a escolherem o plano de internet ideal com base em seu consumo mensal de dados. Para a resolução, você pode solicitar ao usuário que insira o seu consumo, sendo este um valor 'float'. Crie uma função chamada recomendar_plano para receber o consumo médio mensal de dados informado pelo cliente, além de utilizar estruturas condicionais para fazer a verificação e retornar o plano adequado.

### Planos Oferecidos
- Plano Essencial Fibra - 50Mbps: Recomendado para um consumo médio de até 10 GB.
- Plano Prata Fibra - 100Mbps: Recomendado para um consumo médio acima de 10 GB até 20 GB.
- Plano Premium Fibra - 300Mbps: Recomendado para um consumo médio acima de 20 GB.

### Entrada ⬅️
Como entrada solicite o consumo médio mensal de dados em GB (float).

### Saída ➡️
Retorne o plano ideal para o cliente de acordo com o consumo informado na entrada.

### Exemplos 📋
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada | Saída |
|---------|-------|
| 10 | Plano Essencial Fibra - 50Mbps |
| 19 | Plano Prata Fibra - 100Mbps |
| 21 | Plano Premium Fibra - 300Mbps |

# 2 / 3 - Criando uma Lista de Equipamentos 📊
Nível Básico <br>

## Descrição 📒
Você foi designado para desenvolver um programa para gerenciar os equipamentos de uma empresa. O objetivo é criar um solução que permita aos usuários inserir informações sobre os equipamentos que serão cadastrados na rede, em seguida, exibir essa lista de equipamentos. Crie uma Lista para armazenar esses equipamentos e depois um loop para solicitar ao usuário inserir até três equipamentos.

### Entrada ⬅️
O programa solicitará ao usuário que insira uma lista com três equipamentos para adicionar a rede.

### Saída ➡️
Após a entrada dos itens, o programa exibirá a lista de equipamentos inseridos pelo usuário. Cada equipamento será listado com um prefixo ( - ) de marcação para melhor organização.

### Exemplos 📋
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada | Saída |
|---------|-------|
| Antena <br> Roteador <br> Switch | Lista de Equipamentos: <br> - Antena <br> - Roteador <br> - Switch |
| Servidor <br> Cabinet Rack <br> Access Point | Lista de Equipamentos: <br> - Servidor <br> - Cabinet Rack <br> - Access Point |
| Edge Routers <br> Patch Cord <br> UPS | Lista de Equipamentos: <br> - Edge Routers <br> - Patch Cord <br> - UPS |
