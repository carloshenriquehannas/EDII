# EDII
Trabalhos práticos de Estruturas de Dados II.

## Trabalho 1
Deve-se implementar quatro diferentes algoritmos de ordenação (bubble sort, quicksort, radix sort e heapsort). Além disso, também deve-se analisar as complexidades de tempo dos algoritmos. As complexidades dos algoritmos devem ser analisadas em termos teóricos, usando análise assintótica, considerando o melhor caso, o caso médio e o pior caso, e também em termos empíricos, usando medições de tempo de execução.

Para a análise empírica, diferentes tamanhos de sequências devem ser passados para os algoritmos. Os tamanhos das sequências devem crescer por 1 ordem de magnitude por sequência, começando por uma sequência de tamanho 1000. Logo, a primeira sequência deve conter 1000 números; a segunda, 10000 números; a terceira, 100000 números e assim por diante.

Para cada sequência, deve haver 3 variações: uma em que a sequência tem valores aleatórios; uma em que a sequência já está ordenada de maneira crescente e; uma em que a sequência está ordenada de maneira decrescente. O tempo de execução de cada algoritmo para cada sequência para cada variação deve ser medido pelo menos 10 vezes, para evitar variações inesperadas nos tempos de execução. Os tempos devem ser reportados, portanto, com média e desvio padrão.

## Trabalho 2
### Parte 1: Análise de algortimos de busca sequencial
Esta primeira parte do projeto consiste em implementar quatro variações de buscas sequenciais (sequencial simples, sequencial com realocação pelo método mover-para-frente, sequencial com realocação por meio do método da transposição e sequencial por índice primário). O arquivo de entrada contém 50.000 inteiros com valores entre 0 e 50.000. O arquivo de busca contém 50.000 inteiros com valores entre 0 e 70.000. O arquivo de entrada não contém inteiros duplicados. No entanto, o arquivo de busca contém inteiros duplicados e também inteiros que não existem no arquivo de entrada.

### Parte 2: Análise de algoritmos de busca com espalhamento
Esta segunda parte do projeto consiste em implementar três variações de busca com espalhamento. O arquivo de inserção contém 50.000 palavras e o arquivo de busca contém 70.000 palavras. Em ambos os arquivos existem palavras duplicadas, sem acento ou caracteres especiais. Porém, o arquivo de busca contém palavras que não existem no arquivo de inserção. O tamanho máximo de uma palavra é de 20 caracteres.

