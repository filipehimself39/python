# python

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

```
print("Hello World!")
```

Basta utilizar a função **print()**.

Ao executar esse código, a mensagem "Hello World!" será impressa na tela. É importante lembrar de utilizar as aspas para delimitar a mensagem que será impressa.

---

```
a = int(input())
b = int(input())

x = a + b

print("X = {}".format())
```

Primeiro são lidos dois valores inteiros, armazenados nas variáveis a e b. Depois, a soma de a e b é calculada e atribuída à variável x.

---

```
pi = 3.14159
raio = float(input())
area = pi * (raio ** 2)
print("A={:.4f}".format(area))
```

A primeira linha define a constante pi com o valor de 3.14159. Em seguida, o usuário é solicitado a inserir o valor do raio através da função **input()**.

O valor é convertido para ponto flutuante (ou seja, pode assumir valores quebrados) utilizando a função **float()**