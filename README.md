# python

![evangelion_pi](https://user-images.githubusercontent.com/128937668/235545833-92bb7110-05b9-474d-ad90-a724bbee293c.gif)

## Lista de todas as palavras reservadas

**False, True, None:** valores literais que representam, respectivamente, falso, verdadeiro e nenhum valor.

**and, or, not:** operadores lógicos para realizar operações de conjunção, disjunção e negação.

**if, elif, else:** utilizamos para controle de fluxo condicional em um programa.

**while, for, break, continue, in:** utilizamos para controle de fluxo de repetição em um programa.

**def, return:** utilizamos para definir funções e retornar valores a partir delas.

**try, except, finally:** utilizamos para tratamento de exceções em um programa.

**assert, del, pass:** utilizados para testar condições, deletar variáveis e funções e para indicar uma operação vazia, respectivamente.

**import, from, as:** utilizados para importar módulos e submódulos, e para criar um alias para um módulo.

**global, nonlocal:** utilizados para acessar variáveis globais e não locais dentro de funções.

**class, def, super, self:** utilizados para definir e trabalhar com classes e métodos em orientação a objetos.

**lambda:** utilizada para criar funções anônimas (sem nome) de forma mais simples e concisa.

**yield:** utilizada para retornar um valor em uma função geradora, e para permitir pausar e continuar a execução da função.

---

## Hello World!

```
print("Hello World!")

```

Basta utilizar a função **print()**.

Ao executar esse código, a mensagem "Hello World!" será impressa na tela. É importante lembrar de utilizar as aspas para delimitar a mensagem que será impressa.

---

## Extremamente básico

```
# leitura dos valores a e b
a = int(input())
b = int(input())

# cálculo da soma
x = a + b

# exibição do resultado
print("X = {}".format())

```

Primeiro são lidos dois valores inteiros, armazenados nas variáveis a e b. Depois, a soma de a e b é calculada e atribuída à variável x.

---

## Área do círculo

```
pi = 3.14159
raio = float(input())

area = pi * (raio ** 2)

print("A={:.4f}".format(area))

```

A primeira linha define a constante pi com o valor de 3.14159. Em seguida, o usuário é solicitado a inserir o valor do raio através da função **input()**.

O valor é convertido para ponto flutuante (ou seja, pode assumir valores quebrados) utilizando a função **float()**

Um asterisco (*) serve para multiplicar e o uso de dois asteriscos (**) serve para elevar a um número n.

O método **.format** permite que você insira valores em uma string usando marcadores de posição (como {}) que serão substituídos pelos valores passados como argumentos do método. No exemplo acima, usamos "{:.4f}" como marcador de posição, o que significa que o valor passado como argumento (a área calculada) será formatado como um número de ponto flutuante com 4 casas decimais. O resultado será a string "A=valor_da_area_com_4_casas_decimais", que é impressa na tela usando a função print().

---

## Soma simples

```
a = int(input())
b = int(input())

soma = a + b

print("SOMA = {}".format(soma))

```

Primeiro, o código lê os valores de a e b utilizando a função input() e converte-os para inteiros com a função int(). Em seguida, calcula a soma e armazena o resultado na variável soma.

Por fim, exibe o resultado utilizando a função print() e formatando a string com o valor da variável soma.

---

## Produto simples

```
m = int(input())
n = int(input())

produto = m * n

print("PROD = {}".format(produto))

```

Neste código, o programa lê dois valores inteiros a e b a partir da entrada padrão do programa utilizando a função input(). Em seguida, o produto entre a e b é calculado e armazenado na variável produto.

Por fim, exibe o resultado utilizando a função print() e formatando a string com o valor da variável produto.

---

## Média 1

```
nota_a = float(input())
nota_b = float(input())

media = (nota_a * 3.5 + nota_b * 7.5) / 11

print("MEDIA = {:.5f}".format(media))

```

Lê as notas a e b, utilizando a função float() para converter a entrada em valores de ponto flutuante. Depois calcula a média ponderada das notas a e b.

Imprime o resultado da média com 5 casas decimais, utlizando a função print() e utilizando a sintaxe de formatação de string, representada pela função .format() que permite inserir variáveis dentro de uma string formatada usando chaves {} e o símbolo de dois pontos : para especificar o número de casas decimais.

---

## Média 2

```
nota_a = float(input())
nota_b = float(input())
nota c = float(input())

media = (nota_a * 2 + nota_b * 3 + nota_c * 5) / 10

print("MEDIA = {:.1f}".format(media))

```

Primeiro, lemos as notas a, b e c do aluno utilizando a função input() e convertendo o resultado para float utilizando a função float(). Em seguida, calculamos a média ponderada das notas.

Por fim, exibimos a média utilizando a função print(), formatando o resultado para exibir apenas uma casa decimal utilizando a sintaxe de formatação de string {:.1f} e inserindo o valor da variável media utilizando o método .format().

---

## Diferença

```
a = int(input())
b = int(input())
c = int(input())
d = int(input())

diferenca = a * b - c * d

print("DIFERENCA = {}".format(diferenca))

```

Nesse código, as funções int() e input() são usadas para ler os valores inteiros digitados pelo usuário. Em seguida, a fórmula é aplicada para calcular a diferença entre os produtos a * b e c * d, e o resultado é armazenado na variável diferenca.

Por fim, a função print() é usada para imprimir o resultado na tela, utilizando a função .format() para formatar a saída.

---

## Salário

```
numero_funcionario = int(input())
horas_trabalhadas = int(input())
valor_hora = float(input())

salario = horas_trabalhadas * valor_hora

print("NUMBER = {}".format(numero_funcionario))
print("SALARY = R$ {:.2f}".format(salario))

```

Na primeira linha, o programa lê o número do fncionário como um inteiro e armazena na variável numero_funcionario.

Na segunda linha, o programa lê o número de horas trabalhadas como um inteiro e armazena na variável horas_trabalhadas.

Na terceira linha, o programa lê o valor que o funcionario recebe por hora como um número de ponto flutuante e armazena na variável valor_hora.

Na quarta linha, o programa calcula o salário do funcionário multiplicando o número de horas trabalhadas pelo valor da hora trabalhada.

Na quinta linha, o programa imprime o número do funcionário utilizando a função print() e a formatação de string "NUMBER = {}".format (numero_funcionario), onde {} é substituído pelo valor de numero_funcionario.

Na sexta linha, o programa imprime o salário do funcionário utilizando a função print e a formatação de string "SALARY = {:.2f}".format(salario), onde {:.2f} indica que o valor de salario deve ser impresso com duas casas decimais.

---

## Salário com bônus

```
nome_vendedor = input()
salario_fixo = float(input())
total_vendas = float(input())

comissao = total_vendas * 0.15

salario_total = salario_fixo + comissao

print("TOTAL = {:.2f}".format(salario_total))

```

Primeiramente, o códigolê o nome do vendedor utilizando a função input().

Em seguida, lê-se o salário fixo do vendedor e o total de vendas efetuadas, utilizando a função float() para converter as entradas em números de ponto flutuante.

A variável comissao é calculada multiplicando-se o total de vendas por 0.15 (ou 15%).

O salário total é calculado somando-se o salário fixo com a comissão.

Por fim, utiliza-se a função print() para imprimir o salário total, formatando-o com duas casas decimais através do método .format().

---

## Sort simples

```
a, b, c = map(int, input().split())

# cria uma lista com os valores e ordena em ordem crescente
valores_ordenados = sorted([a, b, c])

# imprime os valores ordenados em ordem crescente
print("{}\n{}\n{}".format(valores_ordenados[0], valores_ordenados[1], valores_ordenados[2]))

# imprime uma linha em branco
print()

# imprime os valores na sequência como foram lidos
print("{}\n{}\n{}".format(a, b, c))

```

Nessa solução, usamos a função **map()** para converter os três valores de entrada para inteiros e a função **sorted()** para ordená-los em ordem crescente.

Em seguida, imprimimos os valores ordenados separados por quebras de linha (\n) e imprimimos uma linha em branco com um segundo print() vazio.

Por fim, imprimimos os valores originais na sequência como foram lidos, novamente separados por quebras de linha.

---

## Triângulo

```
a, b, c = map(float, input().split())

# verifica se forma um triângulo
if a + b > c and a + c > b and b + c > a:
    perimetro = a + b + c
    print("Perimetro = {:.1f}".format(perimetro))
else:
    area = ((a + b) * c) / 2
    print("Area = {:.1f}".format(area))

```

A função input() lê a entrada como uma string, que é separada em três valores usando o método **split()**. Os valores são convertidos para float usando a função float() e a função map().

Em seguida, é feita a verificação se forma ou não um triângulo e é calculado o perímetro ou a área, de acordo com o resultado da verificação.

O resultado é impresso na tela usando a função print(), com a formatação desejada usando .format().

---

## Múltiplos

```
a, b = map(int, input().split())

# verifica se são múltiplos
if a % b  == 0 or b % a == 0:
    print("Sao Multiplos")
else:
    print("Nao sao Multiplos")

```

A primeira linha lê os valores de a e b com a função input() e converte-os para inteiros com a função int(). Em seguida, usa a função map() para aplicar a conversão a ambos os valores lidos.

A segunda linha verifica se a é múltiplo de b ou se b é múltiplo de a usando o operador **% (resto da divisão)**. Se o resto for zero em uma dessas verificações, então os valores são múltiplos entre si.

Se os valores são múltiplos, a mensagem "Sao Multiplos" é exibida na tela. Caso contrário, a mensagem "Nao sao Multiplos" é exibida.

---

## Tipos de triângulos

```
a, b, c = map(float, input().split())

# ordenação dos valores em ordem decrescente
maior = max(a, max(b, c))
menor = min(a, min(b, c))
meio = (a + b + c) - maior - menor

# verificação se forma triângulo
if maior >= (meio + menor):
    print("NAO FORMA TRIANGULO")
else:
    # verificação do tipo de triângulo
    if maior ** 2 == meio ** 2 + menor ** 2:
        print("TRIANGULO RETANGULO")
    elif maior ** 2 > meio ** 2 + menor ** 2:
        print("TRIANGULO OBTUSANGULO")
    else:
        print("TRIANGULO ACUTANGULO")

    # verificação se é equilátero ou isósceles
    if a == b == c:
        print("TRIANGULO EQUILATERO")
    elif a == b or b == c or a == c:
        print("TRIANGULO ISOSCELES")

```

Primeiramente, lemos os valores de entrada com a função input() e os convertemos para float(), utilizando a função map() para aplicar a conversão a todos os valores de uma vez.

Em seguida, realizamos a ordenação dos valores em ordem decrescente, para que maior seja o valor de a, e menor seja o valor de b ou c, dependendo da ordem dos valores.

Para encontrar o valor do meio, basta subtrair o valor de maior e menor da soma dos três valores de entrada.

Após a ordenação, verificamos se os valores de entrada formam um triângulo, utilizando a condição maior >= (meio + menor).

Caso não formem, imprimimos a mensagem "NAO FORMA TRIANGULO". Caso contrário, continuamos com a verificação do tipo de triângulo.

Utilizamos a condição maior ** 2 == meio ** 2 + menor ** 2 para verificar se o triângulo é retângulo, e maior ** 2 > meio ** 2 + menor ** 2 para verificar se é obtusângulo. Se nenhum dos dois for verdadeiro o triângulo é acutângulo.

Por fim, verificamos se o triângulo é equilátero ou isósceles. Utilizamos a condição a == b == c para verificar se é equilátero, e a == b or b == c or a == c para verificar se é isósceles.

---

## Tempo de jogo

```
hora_inicial, hora_final = map(int, input().split())

if hora_inicial < hora_final:
    duracao = hora_final - hora_inicial
else:
    duracao = 24 - hora_inicial + hora_final

print("O JOGO DUROU {} HORA(S)".format(duracao))

```

O programa lê as duas horas de entrada e verifica se a hora final é maior que a hora inicial.

Se for, basta subtrair a hora inicial da hora final para obter a duração do jogo. Se a hora final for menor do que a hora inicial, significa que o jogo terminou no dia seguinte, então é preciso somar a hora final com 24 e subtrair a hora inicial para obter a duração.

Por fim, o programa exibe a duração do jogo com a mensagem adequada.
