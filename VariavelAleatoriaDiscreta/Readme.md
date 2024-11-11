Exercicio 01

Temos uma moeda viciada com probabilidade de cara igual a 0,4. Queremos encontrar a probabilidade de obter cara em dois lançamentos independentes.

Espaço amostral

Cara, Cara | Cara, Coroa | Coroa, Cara | Coroa, Coroa

{CC, CK, KC, KK}

Probabilidade de CC = 0,4 * 0,4 = 0,16
Probabilidade de CK = 0,4 * 0,6 = 0,24
Probabilidade de KC = 0,6 * ,04 = 0,24
Probabilidade de KK = 0,6 * 0,6 = 0,36

TABELA FUNÇÃO DE PROBABILIDADE

| Numero de Cara | Probabilidade |
|---|---|
| 0 | 0,36 |
| 1 | 0,48 |
| 2 | 0,16 |

Exercicio 2

Um caminho para uma festa pode ter atrasos em três etapas, cada uma com sua probabilidade. Queremos encontrar a probabilidade de haver atraso e o atraso não passar de 40 minutos.

Simplificando:

Para que o atraso não passe de 40 minutos, as únicas combinações possíveis são:

| Etapa 1 |	Etapa 2	| Etapa 3 | Atraso | Horas |Min |
| --- |---|---|---|---|---|
|Sem|   Sem|    Sem|     0| 1h|(60min)|
|Sem|	Sem|	Com|	30| 1:30h|(90min)|
|Sem|	Com|	Sem|	20| 1:20h|(80min)|
|Sem| Com| Com| 50| 1:50| (110min)|
|Com|	Sem|	Sem|	10| 1:10h|(70min)|
|Com|	Sem|	Com|	40|1:40h|(100min)|
|Com|	Com|	Sem|	30|1:30h|(90min)|
|Com|	Com|	Com|	60|2h|(120min)|

Sem Atraso: (1-0,1)*(1-0,2)*(1-0,3) = 0,504 

Atraso só na primeira etapa: 0,1*(1-0,2)*(1-0,3) = 0,056

Atraso só na segunda etapa:  0,2*(1-0,1)*(1-0,3) = 0,126

Atraso só na Terceira etapa: 0,3*(1-0,1)*(1-0,2) = 0,216

atraso só na primeira e na segunda etapa: 0,2*0,1(1-0,3) = 0,014

Atraso só na primeira e na terceira etapa: 0,3*0,1*(1-0,2) = 0,024 

probabilidade de haver atraso e o atraso não passar de 40 minutos: 

Probabilidade Total: 0,056 + 0,126 + 0,216 + 0,014 + 0,024 = 0,436

a probabilidade de haver algum atraso e o atraso total nao excerder 40 minutos é de 38%

probabilidade de haver atrasos é de 1 - 0,504 = 0,496

49,6%

Exercicio 3

Temos um pai e um filho indo ao cinema. O pai já gastou R$15 com os ingressos. A probabilidade de o filho pedir pipoca é de 0,7 e a de pedir bala é de 0,9. O pai atende a esses pedidos com probabilidade de 0,5 cada. Queremos construir uma tabela com todas as possibilidades de gastos adicionais e suas respectivas probabilidades

P -> Pedir Pipoca
B -> Pedir Bala
A -> Atendido
|A-> Não Atendido

P(p)  = 0,7

P(|p) = 0,3

P(b)  = 0,9

P(|b) = 0,1

P(a)  = 0,5

P(|a) = 0,5


|Pedido de Pipoca|	Pedido de Bala|	Pai atende o pedido de pipoca|	Pai atende o pedido de bala|	Gasto adicional|	Probabilidade|Total (15)|
|---|---|---|---|---|---|---|
|Não	| Não|	- |	- |	0|	0,03|15|
|Sim|	Não|	Sim|	- |	2|	0,7 * 0,5 = 0,35|17|
|Sim	|Não	|Não |	-	|0	|0,7 * 0,5 = 0,35|15|
|Não	|Sim	| -	|Sim	|3	|0,9 * 0,5 = 0,45|18|
|Não	|Sim	| -	|Não	|0	|0,9 * 0,5 = 0,45|15|
|Sim	|Sim	|Sim	|Sim	|5	|0,7 * 0,9 * 0,5 * 0,5 = 0,1575|20|
|Sim	|Sim	|Sim	|Não	|2	|0,7 * 0,9 * 0,5 * 0,5 = 0,1575|17|
|Sim	|Sim	|Não	|Sim	|3	|0,7 * 0,9 * 0,5 * 0,5 = 0,1575|18|


Nenhum pedido: Probabilidade: (1-0,7) * (1-0,9) = 0,3 * 0,1 = 0,03

Apenas pipoca: Probabilidade: 0,7 * 0,5 = 0,35

Apenas bala: Probabilidade: 0,9 * 0,5 = 0,45

Pipoca e bala: Probabilidade: 0,7 * 0,9 * 0,5 * 0,5 = 0,1575

|Pedido	|Gasto Adicional (R$)|	Probabilidade|
|---|---|---|
|Nenhum	|0|	0,03|
|Apenas pipoca|	2	|0,35|
|Apenas bala	|3	|0,45|
|Pipoca e bala|	5	|0,1575|

Gasto Total:

Para encontrar o gasto total, somamos o valor dos ingressos (R$15) ao gasto adicional em cada caso.

|Pedido	|Gasto Total (R$)|	Probabilidade|
|---|---|---|
|Nenhum	|15	|0,03|
|Apenas pipoca|	17|	0,35|
|Apenas bala|	18|	0,45|
|Pipoca e bala|	20	|0,1575|

|G| 15| 17| 18| 20|
|---|---|---|---|---|
|Pi| 0,3575| 0,1925| 0,2925| 0,1575|


Exercicio 4

A função de distribuição acumulada F(x) nos dá a probabilidade de que a variável aleatória X seja menor ou igual a um determinado valor x.
F(x) = p(X<=X)

       |0 se X < 10
       |0,2 se 10 <=x <= 12
F(X) = |0,5 se 12 <= x <=13
       |0,9 se 13 <= x <=25
       |1 se x >= 25



|x |10 |12 |13 |25|
|Pi |0,2 |0,3 |0,4 |0,1| 

Respostas:

a) Função de Probabilidade de X:

A função de probabilidade p(x) nos dá a probabilidade de X assumir exatamente o valor x. Para uma variável aleatória discreta, podemos encontrar p(x) calculando a diferença entre os valores de F(x) nos pontos de salto.

p(10) = F(10) - F(10-) = 0,2 - 0 = 0,2
p(12) = F(12) - F(12-) = 0,5 - 0,2 = 0,3
p(13) = F(13) - F(13-) = 0,9 - 0,5 = 0,4
p(25) = F(25) - F(25-) = 1 - 0,9 = 0,1
Para os demais valores de x, p(x) = 0.

b) P(X ≤ 12):

Diretamente da função de distribuição, P(X ≤ 12) = F(12) = 0,5.

c) P(12 ≤ X ≤ 20):

P(12 ≤ X ≤ 20) = P(X ≤ 20) - P(X < 12) = F(20) - F(12-) = 0,9 - 0,2 = 0,7.

d) P(X > 18):

P(X > 18) = 1 - P(X ≤ 18) = 1 - F(18) = 1 - 0,9 = 0,1.

Explicação:

Função de probabilidade: Calculamos a probabilidade de cada valor específico de X.
Probabilidades acumuladas: Usamos a função de distribuição para encontrar a probabilidade de X ser menor ou igual a um determinado valor.
Probabilidades de intervalos: Subtraímos as probabilidades acumuladas para encontrar a probabilidade de X estar em um intervalo específico.
Complemento: Para encontrar a probabilidade de X ser maior que um valor, calculamos o complemento da probabilidade de X ser menor ou igual a esse valor.