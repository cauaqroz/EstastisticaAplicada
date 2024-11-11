## Resolução dos Exercicios

> Resumo
>   - Analise Combinatoria
>       -  [Lista 6 Exercicios Resolvidos](/AnaliseCombinatoria/Readme.md)
>       - Tabela de Aprendizado
>   - Probabilidade
>       - [Lista 7 Exercicios Resolvidos](/Probabilidade/Readme.md)
>   - Probabilidade Condicional e Eventos Independentes
>       - [Lista 8 Exercicios Resolvidos](/Prob.CondicionalEventosIndependentes/Readme.md)
>   - Probabilidade Total Bayes
>       - [Lista 9 Exercicios Resolvidos](/ProbabilidadeTotal_Bayes/Readme.md)
>   - Variavel Aleatoria Discreta
>       - [Lista 10 Exercicios Resolvidos](/VariavelAleatoriaDiscreta/Readme.md)
>   -Resumo Prova
>       
> <br>
> <br>
> ---
> ---

## Lista de Exercicios para Prova - Resolvida 

### Exercício 1 Usando os Algarismo 1, 3, 4, 6, e 9, Responda:

### a) Quantos números de 4 algarismos distintos podemos formar?

> Temos 5 opções para o primeiro algarismo

> 4 para o segundo (já que um foi usado)

> 3 para o terceiro e 2 para o quarto.

> Então, o total de números é: 

> `5 * 4 * 3 * 2 = 120` números.


### b) Quantos números de 3 algarismos distintos (ou não) podemos formar?

> Para o primeiro algarismo, temos 5 opções.

> Para o segundo, também 5 (pois podem se repetir).

> Para o terceiro, ainda 5 opções.

> Então, o total de números é:

> `5 * 5 * 5 = 125` números.

### Exercício 2 Um levantamento revela as seguintes informações sobre um grupo de pessoas:

| | Gosta de musica | Gosta de Tv | Gosta de cinema | Total |
|---|---|---|---|---|
|homens| 40| 50 | 30 | 120|
|mulheres| 40| 30| 50| 120
|total|80|80|80|240|

#### Definindo que `H`: Homen; `M`: Mulher; `A`: Gosta de Musica; `B`: Gosta de Tv; `C`: Gosta de Cinema, e supondo que cada pessoas deu uma unica resposta, Determine:

### a) p(M/C): Probabilidade de ser mulher, dado que gosta de cinema.



> Total de pessoas que gostam de cinema: 30 + 50 = 80.
 
> Total de mulheres que gostam de cinema: 50.

> `p(M/C) = 50/80 = 5/8`


### b) p(B/M): Probabilidade de gostar de TV, dado que é mulher.

> Total de mulheres: 40 + 50 + 30 = 120.

> Total de mulheres que gostam de TV: 30.

> `p(B/M) = 30/120 = 3/12`

### c) p(H/A): Probabilidade de ser homem, dado que gosta de música.

> Total de pessoas que gostam de música: 40 + 40 = 80.

> Total de homens que gostam de música: 40.

> `p(H/A) = 40/80 = 1/2`

### d) p(A/H): Probabilidade de gostar de música, dado que é homem.

> Total de homens: 40 + 50 + 30 = 120.

> Total de homens que gostam de música: 40.

> `p(A/H) = 40/120 = 1/3`

### Exercício 3:

> Problema de Probabilidade total

#### Probabilidade de uma peça defeituosa:
> Máquina A produz 60% das peças e 2% delas são defeituosas: `0,6 * 0,02 = 0,012`


> Máquina B produz 40% das peças e 8% delas são defeituosas: `0,4 * 0,08 = 0,032`

> Probabilidade total: `0,012 + 0,032 = 0,044 ou 4,4%`

 
## Exercício 4:

> Este é um problema de probabilidade binomial.

Podemos usar a fórmula: `P(X=k) = C(n,k) * p^k * (1-p)^(n-k)`, onde:

>`n` = número de tentativas (7 saltos)

>`k` = número de sucessos (5 saltos)

>`p` = probabilidade de sucesso em cada tentativa (0,3)

>`q` = probabilidade de fracasso em cada tentativa (0,7)

>`C(n,k)` = combinação de n elementos tomados k a k.

>Calculando: `P(X=5) = C(7,5) * 0,3^5 * 0,7^2`

>`C(7,5) = 7!/(5!*2!) = 21`

>`P(X=5) = 21 * 0,00243 * 0,49 = 0,025`

> Probabilidade de acertar 5 lances livres é de aproximadamente 2,5% 


### Exercício 5:

### a) Construa a tabela da função de probabilidade de ocorrer cara:
> C = 0,3

> |C = 0,7

| Número de caras | Probabilidade | 
|---|---| 
| 0 (`/C, /C`) | `(0,7)^2 = 0,49` | 
| 1 (`C, /C` ) | `2 * 0,3 * 0,7 = 0,42` | 
| 2 ( `C, C` ) | `(0,3)^2 = 0,09` |

### b) Determine os valores completos da função de probabilidade: 

|  |  |   |   |
| - |  - | -  | --  | 
|   |{|   0 ;|X < 0 |   |
|   |{|0,49;| 0 <= X < 1 |
|F(X) =|{| |
|   |{|0,91;| 1 <= X < 2 |
|   |{|1;| X >= 2 |