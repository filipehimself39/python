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

