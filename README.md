# Atividades


## Operadores Lógicos


Os operadores lógicos são ferramentas importantes para a codificação de programas e processos, pois eles permitem que os desenvolvedores possam criar condições e tomar decisões baseadas em valores lógicos.

Os principais operadores lógicos utilizados na codificação são: AND, OR e NOT.

O operador AND é utilizado para combinar duas ou mais condições, e a expressão é verdadeira somente se todas as condições forem verdadeiras. Exemplo em C++:
```
if (idade >= 18 && possui_carteira_motorista) {
    // código a ser executado se as duas condições forem verdadeiras
}
```

O operador OR é utilizado para combinar duas ou mais condições, e a expressão é verdadeira se pelo menos uma das condições for verdadeira. Exemplo em Python:
```
if (sexo == 'F' or idade >= 60):
    # código a ser executado se pelo menos uma das condições for verdadeira
```
O operador NOT é utilizado para inverter o valor lógico de uma expressão. Exemplo em Java:
```
if (!(saldo >= 0)) {
    // código a ser executado se a condição for falsa
}
```
Além desses operadores, também é possível utilizar operadores de comparação, como o igual (==), o diferente (!=), o maior (>) e o menor (<), para criar expressões lógicas mais complexas.

Em resumo, os operadores lógicos são uma ferramenta essencial para a codificação de programas e processos, pois permitem que os desenvolvedores possam criar condições e tomar decisões baseadas em valores lógicos.


Dada a expressão booleana S = (A+B).C.(B+D), representar o
circuito lógico correspondente.

![image](https://user-images.githubusercontent.com/57176998/231175855-25d06aca-2a57-4b33-9d0d-152e8334463e.png)


Escreva a expressão booleana executada pelo circuito abaixo:

![image](https://user-images.githubusercontent.com/57176998/231184333-bb9da4d1-b142-4f96-90a0-b584f34c362d.png)

```
(A+B).~C.(~C+~D)
```

Desenhe o circuito lógico cuja expressão característica é S=(~A.~B + ~C.~D)

![image](https://user-images.githubusercontent.com/57176998/231183510-35db8852-13f1-4312-888b-8295f1b371a1.png)

Prove, usando tabela verdade, que os seguintes blocos lógicos são equivalentes:  

![image](https://user-images.githubusercontent.com/57176998/231185686-12dbf6e6-9c7c-4f0f-aca7-2e25d95e0a8d.png)

```
A  B  S1  ~A  ~B  ~A.~B  ~(~A.~B)  S2
0  0   0   1   1     1        0      0
0  1   1   1   0     0        1      1
1  0   1   0   1     0        1      1
1  1   1   0   0     0        1      1

```

Analisando as tabelas verdade de S1 e S2, podemos observar que elas possuem as mesmas colunas de A, B e S. Além disso, as colunas de ~A e ~B são equivalentes às colunas ~A.~B e ~(~A.~B), respectivamente. Portanto, podemos concluir que S1 = A+B e S2 = ~(~A.~B) são equivalentes.

## Exercício 4

Obtenha a expressão de X:

```
A) (A+B).C
B) (A.B)+C
C) ~A.B
D) (~A.~B)
```
## Exercício 5

```
A) (~A+B+C) + (~A.~D)
B) (((~A.~B) + C).D) + E
```

## Exercício 6

```
X = (~A+B).(B+C)

+---+---+---+-------+-------+----+
| A | B | C | ~A+B  | B+C   | X  |
+---+---+---+-------+-------+----+
| 0 | 0 | 0 |  1    |  0    |  0 |
| 0 | 0 | 1 |  1    |  1    |  1 |
| 0 | 1 | 0 |  1    |  1    |  1 |
| 0 | 1 | 1 |  1    |  1    |  1 |
| 1 | 0 | 0 |  1    |  0    |  0 |
| 1 | 0 | 1 |  0    |  1    |  0 |
| 1 | 1 | 0 |  1    |  1    |  1 |
| 1 | 1 | 1 |  0    |  1    |  0 |
+---+---+---+-------+-------+----+

```

## Exercício 7

![image](https://user-images.githubusercontent.com/57176998/231189873-29e393cb-0a4d-4855-83d3-3e141a7424fb.png)








