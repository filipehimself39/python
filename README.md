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

---

## Tempo de jogo com minutos

```
x = input().split()
hi, mi, hf, mf = x

hi = int(x[0])
mi = int(x[1])
hf = int(x[2])
mf = int(x[3])

if hi < hf:
    h = hf - hi
    if mi < mf:
        m = mf - mi
    if mi > mf:
        h = h - 1
        m = (60 - mi) + mf
    if mi == mf:
        m = 0
if hi > hf:
    h = (24 - hi) + hf
    if mi < mf:
        m = mf - mi
    if mi > mf:
        h = h - 1
        m = (60 - mi) + mf
    if mi == mf:
        m = 0
if hi == hf:
    if mi < mf:
        m = mf - mi
        h = 0
    if mi > mf:
        m = (60 - mi) + mf
        h = 23
    if mi == mf:
        h = 24
        m = 0
    
print('O JOGO DUROU {} HORA(S) E {} MINUTO(S)'.format(h, m))

```

Este código lê quatro números inteiros que representam a hora inicial e final de um jogo e calcula a duração do jogo em horas e minutos. O código tem três blocos condicionais, um para cada caso em que a hora inicial é menor, maior ou igual à hora final. Para calcular a duração do jogo, o código faz a diferença entre as horas e minutos iniciais e finais, e ajusta os valores de acordo com as condições de hora e minuto.

---

## Aumento de salário

```
salario = float(input())

if salario <= 400:
    percentual = 15
elif salario <= 800:
    percentual = 12
elif salario <= 1200:
    percentual = 10
elif salario <= 2000:
    percentual = 7
else:
    percentual = 4

reajuste = salario * percentual / 100
novo_salario = salario + reajuste

print("Novo salario: {:.2f}".format(novo_salario))
print("Reajuste ganho: {:.2f}".format(reajuste))
print("Em percentual: {} %".format(percentual))

```

O código lê o salário do funcionário e verifica em qual faixa de salário ele se encaixa, de acordo com a tabela de percentuais de reajuste.

Em seguida, calcula o valor do reajuste e o novo salário do funcionário. Por fim, imprime as informações pedidas.

---

## Animal

```
# lendo as três palavras
palavra1 = input().lower()
palavra2 = input().lower()
palavra3 = input().lower()

# verificando qual o animal escolhido
if palavra1 == 'vertebrado':
    if palavra2 == 'ave':
        if palavra3 == 'carnivoro':
            animal = 'aguia'
        else:
            animal = 'pomba'
    else:
        if palavra3 == 'onivoro':
            animal = 'homem'
        else:
            animal = 'vaca'
else:
    if palavra2 == 'inseto':
        if palavra3 == 'hematofago':
            animal = 'pulga'
        else:
            animal = 'lagarta'
    else:
        if palavra3 == 'hematofago':
            animal = 'sanguessuga'
        else:
            animal = 'minhoca'

# imprimindo o animal escolhido
print(animal)

```

O programa lê as três palavras, converte todas as letras para minúsculas (com o método .lower()) e verifica qual o animal escolhido, utilizando a estrutura condicional.

Se a primeira palavra for "vertebrado", o programa verifica se a segunda palavra é "ave" ou "mamifero". Se for "ave", o programa verifica se a terceira palavra é "carnivoro" ou "onivoro".

Dependendo das respostas, o programa define qual o animal escolhido (águia, pomba, homem ou vaca). Se a primeira palavra for "invertebrado", o programa segue um caminho semelhante, mas com outros animais possíveis (pulga, lagarta, sanguessuga ou minhoca).

Por fim, o programa imprime o animal escolhido.

---

## DDD

```
ddd = int(input())

if ddd == 61:
    print("Brasilia")
elif ddd == 71:
    print("Salvador")
elif ddd == 11:
    print("Sao Paulo")
elif ddd == 21:
    print("Rio de Janeiro")
elif ddd == 32:
    print("Juiz de Fora")
elif ddd == 19:
    print("Campinas")
elif ddd == 27:
    print("Vitoria")
elif ddd == 31:
    print("Belo Horizonte")
else:
    print("DDD nao cadastrado")

```

Primeiramente, a entrada do DDD é lida como um inteiro utilizando a função int(input()).

Em seguida, é feita uma série de comparações utilizando o comando if para verificar qual é o DDD informado e imprimir o nome da cidade correspondente.

Caso o DDD não esteja presente na tabela, é impressa a mensagem "DDD nao cadastrado" utilizando o comando else.

---

## Positivos e média

```
# lendo os 6 valores
valores = []
for i in range(6):
    valores.append(float(input()))

# contando os valores positivos
positivos = sum([1 for v in valores if v > 0])

# calculando a média dos valores positivos
media_positivos = sum([v for v in valores if v > 0]) / positivos

# imprimindo o resultado
print("{} valores positivos".format(positivos))
print("{:.1f}".format(media_positivos))

```

Na primeira parte do código, lemos os 6 valores e armazenamos em uma lista chamada valores. Em seguida, utilizamos a função sum em conjunto com uma lista comprehension para contar quantos valores positivos existem na lista. Note que estamos usando a sintaxe [1 for v in valores if v > 0] para criar uma lista com valores 1 para cada elemento da lista valores que for positivo. Depois, usamos a função sum para somar todos esses valores, obtendo o total de valores positivos.

Na segunda parte do código, usamos novamente a função sum em conjunto com uma lista comprehension para somar todos os valores positivos da lista valores. Em seguida, dividimos esse valor pelo total de valores positivos para obter a média, que é armazenada na variável media_positivos.

Por fim, usamos a função print para imprimir o resultado. Usamos a função format para formatar as mensagens, inserindo os valores das variáveis positivos e media_positivos. Na segunda mensagem, usamos a opção :.1f para imprimir a média com apenas um dígito após o ponto decimal.

---

## Revisão de contrato

```
while True:
    d, n = input().split()
    
    if d == "0" and n == "0":
        break
        
    new_n = ""
    for digit in n:
        if digit != d:
            new_n += digit
            
    if new_n == "":
        print(0)
    else:
        print(int(new_n))

```

Para cada caso de teste, o programa lê uma linha com dois números separados por espaço, sendo o primeiro o dígito com falha e o segundo o número original do contrato.

Em seguida, é criada uma nova string new_n que representa o número sem o dígito com falha.

Depois, o programa verifica se a string new_n é vazia, o que significa que o número original só tinha o dígito com falha. Nesse caso, o programa imprime 0.

Caso contrário, o programa converte a string new_n em um inteiro usando a função int e imprime o resultado.

---

## Frequência de números

```
qte = int(input())
lista = {}
for i in range(qte):
    v = int(input())
    if(v in lista):
        lista[v] += 1
    else:
        lista[v] = 1


chaves = lista.keys()
chaves = sorted(chaves)

for k in chaves:
    print("%d aparece %d vez(es)" %(k,lista[k]))

```

O código apresentado é uma solução correta para o problema de contar a frequência de cada valor em uma lista de inteiros. O algoritmo utiliza um dicionário para armazenar a contagem de ocorrências de cada valor na lista, percorrendo a lista e incrementando o valor correspondente no dicionário para cada elemento encontrado.

Em seguida, o código ordena as chaves do dicionário (os valores únicos presentes na lista) e itera sobre elas, imprimindo a contagem correspondente a cada valor.

A complexidade do algoritmo é linear em relação ao tamanho da lista de entrada, já que é necessário percorrer cada elemento uma única vez para fazer a contagem. O uso do dicionário permite que a contagem seja feita com complexidade constante para cada elemento da lista, já que a operação de adicionar um elemento a um dicionário é de tempo médio constante em Python.

---

## Substituição em vetor 1

```
# lê o vetor X
X = []
for i in range(10):
    X.append(int(input()))

# substitui os valores negativos e nulos por 1
for i in range(10):
    if X[i] <= 0:
        X[i] = 1

# mostra o vetor X
for i in range(10):
    print("X[{}] = {}".format(i, X[i]))

```

Explicando o código, primeiramente é lido o vetor X com 10 valores inteiros. Em seguida, é feito um loop para percorrer o vetor e substituir os valores negativos e nulos por 1. Por fim, é feito outro loop para mostrar o vetor X já modificado.

Note que a linha X.append(int(input())) lê um valor inteiro do usuário e adiciona ao final do vetor X. Já a linha print("X[{}] = {}".format(i, X[i])) mostra o valor de X na posição i, utilizando formatação de string para exibir corretamente o índice e o valor.

---

## Preenchimento de vetor 1

```
v = int(input())  # lê o valor inteiro

n = [v]  # cria o vetor com o valor lido na primeira posição

for i in range(1, 10):
    n.append(n[i-1] * 2)  # adiciona ao vetor o dobro do valor anterior

# imprime o vetor formatado
for i in range(10):
    print("N[{}] = {}".format(i, n[i]))

```

O programa lê o valor inteiro v e cria um vetor n com esse valor na primeira posição.

Em seguida, um laço for é utilizado para preencher as posições subsequentes do vetor com o dobro do valor da posição anterior.

Por fim, outro laço for é utilizado para imprimir o vetor formatado com as posições e seus respectivos valores.

---

## Seleção em vetor 1

```
# lê os valores do vetor A
A = []
for i in range(100):
    A.append(float(input()))

# procura os valores menores ou iguais a 10
for i in range(100):
    if A[i] <= 10:
        print("A[{}] = {:.1f}".format(i, A[i]))

```

O programa lê os 100 valores do vetor A e, em seguida, percorre o vetor procurando por valores menores ou iguais a 10.

Quando encontra um valor desses, imprime a posição e o valor correspondente utilizando a função .format() para formatar a saída com uma casa decimal.

---

## Troca em vetor 1

```
# lê os valores do vetor
vetor = []
for i in range(20):
    valor = int(input())
    vetor.append(valor)

# troca os elementos do vetor
for i in range(10):
    j = 19 - i
    aux = vetor[i]
    vetor[i] = vetor[j]
    vetor[j] = aux

# mostra o vetor modificado
for i in range(20):
    print("N[{}] = {}".format(i, vetor[i]))

```

Primeiro, o programa lê os valores do vetor N, armazenando-os em uma lista chamada vetor.

Em seguida, ele realiza as trocas de elementos do vetor usando um loop que varre do primeiro até o décimo elemento do vetor, trocando com o elemento correspondente do final do vetor.

Por fim, o programa mostra o vetor modificado usando outro loop que varre todas as posições do vetor, imprimindo o índice e o vetor correspondente usando a formatação especificada.

---

## Fibonacci em vetor

```
t=int(input())
for i in range(t):
    x=int(input())
    f=[0,1]
    if x>1:
        for j in range(2,x+1):
           
            f.append(f[j-2]+f[j-1])
        print('Fib({}) = {}'.format(x,f[x]))
    if x <=1:
        print('Fib({}) = {}'.format(x,f[x]))

```

O código dado é uma implementação do algoritmo para encontrar o número de Fibonacci correspondente a um número inteiro informado pelo usuário. O programa utiliza um loop para preencher uma lista com os números da sequência de Fibonacci até o número informado. Em seguida, o número correspondente é exibido na tela.

Abaixo está uma explicação passo a passo do código:

A primeira linha lê um inteiro t, que indica o número de testes que serão realizados.

O loop for é executado t vezes e para cada iteração:

É lido um inteiro x que indica qual número de Fibonacci deve ser encontrado.

É criada uma lista f com os dois primeiros números da sequência de Fibonacci, que são 0 e 1.

Se x for maior que 1, um loop for é executado para adicionar os próximos números da sequência de Fibonacci na lista f.

Cada número adicionado na lista é a soma dos dois números anteriores da sequência.

Após preencher a lista com todos os números da sequência até o número x, o valor correspondente é exibido na tela usando a função print() e uma string formatada.

Se x for menor ou igual a 1, o valor correspondente é exibido diretamente, sem a necessidade de criar a lista f.

No geral, o programa funciona corretamente para encontrar os números de Fibonacci correspondentes aos valores informados pelo usuário.

---

## Preenchimento de vetor 4

```
# Inicializa os vetores de números pares e ímpares
pares = []
impares = []

# Loop para ler os 15 números
for i in range(15):
    num = int(input())

    # Se o número é par, adiciona no vetor de pares
    if num % 2 == 0:
        pares.append(num)

        # Se o vetor de pares encheu, imprime e reinicializa
        if len(pares) == 5:
            for j in range(5):
                print("par[{}] = {}".format(j, pares[j]))
            pares = []

    # Se o número é ímpar, adiciona no vetor de ímpares
    else:
        impares.append(num)

        # Se o vetor de ímpares encheu, imprime e reinicializa
        if len(impares) == 5:
            for j in range(5):
                print("impar[{}] = {}".format(j, impares[j]))
            impares = []

# Imprime os números que sobraram nos vetores
for i in range(len(impares)):
    print("impar[{}] = {}".format(i, impares[i]))

for i in range(len(pares)):
    print("par[{}] = {}".format(i, pares[i]))

```

O código acima realiza a leitura de 15 números inteiros, armazenando-os em dois vetores diferentes: um para números pares e outro para ímpares. A medida que cada vetor enche com 5 elementos, o código os imprime na tela e reinicializa o vetor. No final, o código imprime os elementos restantes nos vetores que não foram impressos.

O código funciona da seguinte forma:

Inicializa os vetores de pares e ímpares vazios.

Realiza um loop para ler os 15 números.

Se o número lido é par, adiciona-o no vetor de pares e verifica se o vetor encheu. Se sim, imprime os números pares armazenados e reinicializa o vetor.

Se o número lido é ímpar, adiciona-o no vetor de ímpares e verifica se o vetor encheu. Se sim, imprime os números ímpares armazenados e reinicializa o vetor.

Após a leitura dos 15 números, imprime os elementos que sobraram nos vetores de pares e ímpares que não foram impressos.

O código é uma forma de particionar um conjunto de números inteiros em dois vetores separados por paridade, e imprimir esses vetores de maneira organizada na tela.

---

## Menor e posição

```
n = int(input())
x = list(map(int, input().split()))

menor = x[0]
posicao = 0

for i in range(1, n):
    if x[i] < menor:
        menor = x[i]
        posicao = i

print("Menor valor:", menor)
print("Posicao:", posicao)

```

O programa começa lendo o tamanho do vetor N e em seguida lendo os valores do vetor X. Em seguida, o programa percorre todo o vetor X, comparando cada valor com o menor valor encontrado até então.

Caso encontre um valor menor, atualiza a variável menor e a posição do menor valor no vetor X na variável posicao.

Por fim, o programa exibe o menor valor e a sua posição no vetor.

---

## Linha na matriz

```
matriz = []
soma = 0.0
indice = int(input())
opecacao = input()
for i in range(12):
  linha = []
  for j in range(12):
    numero = float(input())
    linha.append(numero)
  matriz.append(linha)

for a in range(12):
  for b in range(12):
    if a == indice:
      soma+=matriz[a][b]

if opecacao == "S":      
  print("%.1f"%soma)      
elif opecacao == "M":
  print("%.1f"%(soma/12))
```

O código apresentado parece estar correto e realiza a soma ou média dos elementos de uma linha da matriz, conforme indicado pelo usuário. No entanto, é importante lembrar que ele assume que a matriz tem sempre dimensões 12x12 e que os valores de entrada estão corretos e seguem o formato esperado.

Uma possível sugestão de melhoria seria adicionar validações para garantir que o índice de linha informado pelo usuário esteja dentro dos limites da matriz e que o tipo de operação informada seja válido (apenas "S" ou "M"). Isso evitaria erros no programa caso essas condições não sejam atendidas.

---

## Coluna na matriz

```
coluna = int(input())
operacao = input().upper()

matriz = []

for i in range(12):
    linha = []
    for j in range(12):
        linha.append(float(input()))
    matriz.append(linha)

soma = 0
for i in range(12):
    soma += matriz[i][coluna]

if operacao == 'S':
    print("{:.1f}".format(soma))
else:
    media = soma / 12
    print("{:.1f}".format(media))

```

Primeiro, lemos o número da coluna e a operação desejada (soma ou média).

Em seguida, criamos a matriz lendo os 144 elementos de entrada, linha por linha.

Depois, percorremos os elementos da coluna desejada e somamos seus valores na variável soma.

Por fim, verificamos se a operação desejada é soma ou média e imprimimos o resultado formatado com uma casa decimal utilizando o método format().

---

## Acima da diagonal principal

```
operacao = input()  # lê a operação a ser realizada
matriz = []  # inicializa a matriz
soma = media = 0  # inicializa as variáveis de soma e média

# lê os valores da matriz
for i in range(12):
    linha = []
    for j in range(12):
        linha.append(float(input()))
    matriz.append(linha)

# calcula a soma ou a média dos elementos acima da diagonal principal
for i in range(12):
    for j in range(i+1, 12):
        soma += matriz[i][j]
if operacao == 'S':
    resultado = soma
else:
    resultado = soma / 66  # há 66 elementos acima da diagonal principal

# exibe o resultado formatado com uma casa decimal
print("{:.1f}".format(resultado))

```

A ideia do programa é ler a operação e a matriz da entrada, calcular a soma ou a média dos elementos acima da diagonal principal e exibir o resultado formatado com uma casa decimal.

Para isso, o programa utiliza um laço duplo para percorrer os elementos acima da diagonal principal (ou seja, aqueles em que o índice da linha é menor do que o índice da coluna). Em seguida, a soma ou a média é calculada de acordo com a operação escolhida.

Note que o resultado da média é dividido por 66, que é o número de elementos acima da diagonal principal em uma matriz 12x12.

O número de elementos é fixo neste caso, mas para uma matriz genérica, é possível calcular o número de elementos acima da diagonal principal como a soma dos números de 1 a n-1, onde n é o número de linhas ou colunas da matriz.

---

## Combinador

```
n = int(input())

for i in range(n):
    s1, s2 = input().split()
    result = ""
    len_s1, len_s2 = len(s1), len(s2)
    for j in range(max(len_s1, len_s2)):
        if j < len_s1:
            result += s1[j]
        if j < len_s2:
            result += s2[j]
    print(result)

```

Primeiramente, lemos o número de casos de teste n.

Em seguida, utilizamos um loop for para iterar sobre cada caso de teste.
Dentro do loop, lemos as duas strings s1 e s2 separadas por espaço.
Em seguida, inicializamos a string result que será a string resultante da combinação.

Obtemos o comprimento de cada string utilizando a função len().
Em seguida, utilizamos outro loop for para iterar sobre o comprimento máximo entre as duas strings.

Dentro do loop, verificamos se ainda há letras para adicionar na string resultante result a partir da string s1 e s2, utilizando os índices j e o comprimento de cada string.

Por fim, imprimimos a string resultante result.

---

## Matriz quadrada 2

```
while True:
    N = int(input())

    if (N == 0):
        break

    resultado =  []

    for i in range(1,(N+1)):
        tmp = []
        count = i
        for j in range(N):
            tmp.append(abs(count))
            if(count == 1):
                count -= 3
            else:
                count -= 1
        resultado.append(tmp)

    for i in range(N):
        tx = ''
        for j in range(N):
            tx += " %3d" %resultado[i][j]
        print(tx[1:])
    print("")

```
O código apresentado é um algoritmo em Python que lê um inteiro N e, a partir dele, cria uma matriz com valores que seguem um padrão específico. Depois, o algoritmo imprime essa matriz na tela.

O algoritmo usa um loop while True para garantir que as instruções sejam executadas enquanto não for digitado um valor N igual a 0. Dentro do loop, o algoritmo cria uma lista vazia chamada resultado, que será preenchida com os valores da matriz. Em seguida, há um loop for que itera de 1 até N+1 (pois o range não inclui o último valor). Esse loop cria uma lista tmp vazia e uma variável count que recebe o valor de i.

O loop interno for que segue é responsável por preencher a lista tmp com valores. A cada iteração desse loop, é adicionado à lista tmp o valor absoluto da variável count. Depois disso, a variável count é decrementada em 1 (ou em 3, caso count seja igual a 1).

Ao final de cada iteração do loop externo for, a lista tmp é adicionada à lista resultado. Após o preenchimento da lista resultado, há um novo loop for que itera de 0 até N (pois a lista começa em 0). Esse loop cria uma string tx vazia e, a cada iteração, adiciona à string tx o valor da lista resultado correspondente à linha i e à coluna j. É adicionado um espaço em branco e o formato de exibição "%3d" antes do valor para que o resultado seja apresentado com três caracteres e alinhado à direita. Depois de preencher a string tx, o algoritmo imprime na tela todos os caracteres da string tx, exceto o primeiro espaço em branco.

Ao final de cada conjunto de valores para um valor de N específico, é impressa uma linha em branco para separar os conjuntos.
