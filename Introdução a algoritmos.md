# Livro: Entendendo algoritmos
_Autor: A. Y. Bhargava_
_Resumo por: AnaCaFe_

**Definição:** Um algoritmo é um conjunto de instruções que realizam uma tarefa.


## 1. Pesquisa Binária

## 2. Tempo de execução
* Voltando à pesquisa simples, quanto tempo se otimiza utilizando-a? Bem, a primeira abordagem seria verificar número por número. Se fosse uma lista de 100 números, precisaríamos de 100 tentativas. Se fosse uma lista de 4 bilhões de números, precisaríamos de 4 bilhões de tentativas. Logo, o número máximo de tentativas é igual ao tamanho da lista. Isso é chamado de tempo linear.
* A pesquisa binária é diferente. Se a lista tem 100 itens, precisa-se de, no máximo, sete tentativas. Se tem 4 bilhões, precisa-se de, no máximo, 32 tentativas. A pesquisa binária é executada com tempo logarítmico.
* A rapidez de um algoritmo não é medida em segundos, mas pelo crescimento do número de operações.
* Em vez disso, discutimos sobre o quão rapidamente o tempo de execução de um algoritmo aumenta conforme o número de elementos aumenta.
* O tempo de execução em algoritmos é expresso na notação Big O. 
* O(log n) é mais rápido do que O(n), e O(log n) fica ainda mais rápido conforme a lista aumenta.

# A notação Big O
* Diz a velocidade do algoritmo
* O tempo de execução dos algoritmos cresce a taxas diferentes
    * A notação Big O estabelece o tempo de execução para a pior hipótese
    * alguns tempos de execução Big O:
        * O(log n), também conhecido como tempo logarítmico. Exemplo: pesquisa binária.
        * O(n), conhecido como tempo linear. Exemplo: pesquisa simples.
        * O(n * log n). Exemplo: um algoritmo rápido de ordenação, como a ordenação quicksort (explicada no Capítulo 4).
        * O(n2). Exemplo: um algoritmo lento de ordenação, como a ordenação por seleção (explicada no Capítulo 2).
        * O(n!). Exemplo: um algoritmo bastante lento, como o do caixeiro viajante.

## 3. O problema do caixeiro viajante: O(n!)


# Ordenação por seleção
* A memória do seu computador é como um conjunto gigante de gavetas. 
* Quando se quer armazenar múltiplos elementos, usa-se um array ou uma lista.
* No array, todos os elementos são armazenados um ao lado do outro.
* Na lista, os elementos estão espalhados e um elemento armazena o endereço do próximo elemento.
* Arrays permitem leituras rápidas.
* Listas encadeadas permitem rápidas inserções e eliminações.
* Todos os elementos de um array devem ser do mesmo tipo (todos ints, todos doubles, e assim por diante).

# Recursão
**“Os loops podem melhorar o desempenho do seu programa. A recursão melhora o desempenho do seu programador. Escolha o que for mais importante para a sua situação."**

* Recursão é quando uma função chama a si mesma.
* Toda função recursiva tem dois casos: o caso-base e o caso recursivo.
* Uma pilha tem duas operações: push e pop.
* Todas as chamadas de função vão para a pilha de chamada.
* A pilha de chamada pode ficar muito grande e ocupar muita memória.
* Lembre-se de que a recursão tem memória dos estados anteriores.


```
Quando estiver escrevendo uma função de recursão que envolva um array, o caso-base será, muitas vezes, um array vazio ou um array com apenas um elemento. Se estiver com problemas, use este caso como base.
```

# Quicksort


#### Dividir para conquistar
1. Descubra o caso-base, que deve ser o caso mais simples possível.
2. Divida ou diminua o seu problema até que ele se torne o caso-base.

