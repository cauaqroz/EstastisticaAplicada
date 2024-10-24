## Resolução dos Exercícios

### Conceitos básicos:

>[!Important] 
> Permutação: É a ordenação de elementos de um conjunto.
> 
>[!Important] 
> Combinação: É a escolha de elementos de um conjunto, sem levar em consideração a ordem.

>[!Important] 
> Arranjo: É a escolha de elementos de um conjunto, levando em consideração a ordem.

### 1) Quantos números de 3 algarismos distintos podemos formar com 5, 6 e 8?

#### Passo a passo:
**A ordem dos algarismos importa, pois 568 é diferente de 865. Estamos formando arranjos simples.**

> Primeiro algarismo: Temos tantas opções quantos são os algarismos disponíveis.

> Segundo algarismo: Uma opção a menos que o primeiro, pois não podemos repetir.

> Terceiro algarismo: Uma opção a menos que o segundo.

> Multiplicamos as possibilidades de cada casa para obter o total.
Temos: 
- 3 opções para o primeiro algarismo
- 2 opções para o segundo
- 1 opção para o terceiro.

> Pela regra do produto: 3 * 2 * 1 = 6 números.

### 2) Quantos números de 3 algarismos distintos podemos formar com 1, 3, 4, 6 e 9?

#### Passo a passo:
**A ordem dos algarismos importa, pois 568 é diferente de 865. Estamos formando arranjos simples.**

> Primeiro algarismo: Temos tantas opções quantos são os algarismos disponíveis.

> Segundo algarismo: Uma opção a menos que o primeiro, pois não podemos repetir.

> Terceiro algarismo: Uma opção a menos que o segundo.

> Multiplicamos as possibilidades de cada casa para obter o total.
Temos: 

- 5 opções para o primeiro
- 4 opções para o segundo
- 3 opções para o terceiro.

> 5 * 4 * 3 = 60 números.


### 3) Quantas comissões diferentes de 3 pessoas podemos formar com 10 pessoas?

#### Passo a passo:
**Queremos formar grupos de 3 pessoas, e a ordem em que escolhemos as pessoas não importa (João, Maria, Pedro é a mesma comissão que Maria, João, Pedro). Estamos falando de combinações simples.**

> Usamos a fórmula de combinação para calcular o número de grupos possíveis.

>A ordem não importa, então dividimos o número de permutações pelo número de repetições.

- Usamos a fórmula C(n, k) = n! / (k! * (n-k)!)
- n! é o fatorial de n
- k! é o fatorial de k
- (n-k)! é o fatorial de n-k

- n = 10 (total de pessoas)
- k = 3 (número de pessoas por comissão)

> C(10,3) = 10! / (3! * 7!) = 120 comissões.


### 4) Quantos anagramas tem a palavra BANANA?

#### Passo a passo:
**Queremos rearranjar as letras da palavra, mas temos letras repetidas. Estamos lidando com permutações com repetição.**
> Calculamos o número de permutações como se todas as letras fossem diferentes.

> Dividimos pelo fatorial do número de repetições de cada letra.

- Temos 6 letras, sendo:
- 3 A's
- 2 N's 
- 1 B.

> A fórmula para anagramas com repetição é:
 
> n! / (n1! * n2! * ... * nk!)
- onde n é o número total de elementos
-  ni é o número de repetições do elemento i.
  
- 6! / (3! * 2! * 1!) = 60 anagramas.

### 5) Quantos números naturais de 2 algarismos podemos formar com 4, 7, 8 e 9?

#### Passo a passo:

> Algarismos distintos: É um arranjo simples, similar aos exercícios 1 e 2.

> Algarismos com repetição: Podemos repetir os algarismos, então multiplicamos as possibilidades para cada casa.
- Temos 4 opções para cada casa, pois a repetição é permitida.
> 4 * 4 = 16 números.

### 6) Quantas placas diferentes de automóvel podem ser feitas com 3 letras e 4 números?
#### Passo a passo:
> Letras: Arranjo simples, pois a ordem importa e não repetimos letras.

> Números: Arranjo com repetição, pois a ordem importa e podemos repetir números.

> Total: Multiplicamos as possibilidades de letras e números.
- Para as letras: 26 * 25 * 24 (sem repetição).
- Para os números: 10 * 10 * 10 * 10 (com repetição).

> Total: 26 * 25 * 24 * 10 * 10 * 10 * 10 = 156.000.000 placas.

