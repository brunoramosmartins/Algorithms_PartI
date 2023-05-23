# Algorithms, Part I   
*by Universidade de Princeton*

## Sobre este Curso

Este curso cobre as informações essenciais que todo programador sério precisa saber sobre algoritmos e estruturas de dados, com ênfase em aplicações e análise de desempenho científico de implementações Java. A Parte I abrange estruturas de dados elementares, classificação e algoritmos de pesquisa. A Parte II concentra-se em algoritmos de processamento de gráficos e strings.

## Semana 1

- Course Introduction
- Union−Find:

    Ilustramos nossa abordagem básica para desenvolver e analisar algoritmos considerando o problema de conectividade dinâmica. Introduzimos o tipo de dados union-find e consideramos várias implementações (quick find, quick union, weighted quick union e weighted quick union com compressão de caminho). Finalmente, aplicamos o tipo de dados union-find ao problema de percolação da físico-química.

- Analysis of Algorithms

    A base da nossa abordagem para analisar o desempenho dos algoritmos é o método científico. Começamos realizando experimentos computacionais para medir os tempos de execução de nossos programas. Usamos essas medições para desenvolver hipóteses sobre o desempenho. Em seguida, criamos modelos matemáticos para explicar seu comportamento. Por fim, consideramos a análise do uso de memória de nossos programas Java.

## Semana 2

- Stacks and Queues

    Consideramos dois tipos de dados fundamentais para armazenar coleções de objetos: a pilha e a fila. Implementamos cada um usando uma lista vinculada individualmente ou uma matriz de redimensionamento. Apresentamos dois recursos Java avançados — genéricos e iteradores — que simplificam o código do cliente. Finalmente, consideramos várias aplicações de pilhas e filas, desde a análise de expressões aritméticas até a simulação de sistemas de filas.

- Elementary Sorts

    Apresentamos o problema de ordenação e a interface Comparable de Java. Estudamos dois métodos elementares de ordenação (ordenação por seleção e ordenação por inserção) e uma variação de um deles (shellsort). Também consideramos dois algoritmos para embaralhar uniformemente um array. Concluímos com uma aplicação de classificação para calcular o casco convexo por meio do algoritmo de varredura de Graham.

## Semana 3

- Mergesort

    Estudamos o algoritmo mergesort e mostramos que ele garante a ordenação de qualquer array de n itens com no máximo n lg n comparações. Também consideramos uma versão não recursiva de baixo para cima. Provamos que qualquer algoritmo de classificação baseado em comparação deve fazer pelo menos n lg n comparações no pior caso. Discutimos o uso de diferentes ordenações para os objetos que estamos classificando e o conceito relacionado de estabilidade.

- Quicksort

    Introduzimos e implementamos o algoritmo randomizado de quicksort e analisamos seu desempenho. Também consideramos a seleção rápida aleatória, uma variante de classificação rápida que encontra o k-ésimo menor item em tempo linear. Finalmente, consideramos o quicksort de 3 vias, uma variante do quicksort que funciona especialmente bem na presença de chaves duplicadas.

## Semana 4

- Priority Queues

    Apresentamos o tipo de dados fila de prioridade e uma implementação eficiente usando a estrutura de dados heap binário. Essa implementação também leva a um algoritmo de classificação eficiente conhecido como heapsort. Concluímos com uma aplicação de filas de prioridade onde simulamos o movimento de n partículas sujeitas às leis de colisão elástica.

- Elementary Symbol Tables

    Definimos uma API para tabelas de símbolos (também conhecidas como matrizes associativas, mapas ou dicionários) e descrevemos duas implementações elementares usando uma matriz classificada (pesquisa binária) e uma lista não ordenada (pesquisa sequencial). Quando as chaves são comparáveis, definimos uma API estendida que inclui os métodos adicionais min, max floor, roof, rank e select. Para desenvolver uma implementação eficiente dessa API, estudamos a estrutura de dados da árvore de busca binária e analisamos seu desempenho.

## Semana 5

- Balanced Search Trees

    Nesta palestra, nosso objetivo é desenvolver uma tabela de símbolos com desempenho logarítmico garantido para busca e inserção (e muitas outras operações). Começamos com 2 a 3 árvores, que são fáceis de analisar, mas difíceis de implementar. Em seguida, consideramos árvores binárias de busca vermelho-preto, que vemos como uma nova maneira de implementar árvores 2-3 como árvores binárias de busca. Finalmente, introduzimos B-trees, uma generalização de 2-3 árvores que são amplamente utilizadas para implementar sistemas de arquivos.

- Geometric Applications of BSTs

    Começamos com a busca de intervalo 1d e 2d, onde o objetivo é encontrar todos os pontos em um determinado intervalo 1d ou 2d. Para conseguir isso, consideramos kd-trees, uma generalização natural de BSTs quando as chaves são pontos no plano (ou dimensões superiores). Também consideramos problemas de interseção, onde o objetivo é encontrar todas as interseções entre um conjunto de segmentos de reta ou retângulos.

## Semana 6

- Hash Tables

    Começamos descrevendo as propriedades desejáveis da função hash e como implementá-las em Java, incluindo um princípio fundamental conhecido como suposição de hash uniforme que fundamenta o sucesso potencial de um aplicativo de hash. Em seguida, consideramos duas estratégias para implementar tabelas de hash — encadeamento separado e sondagem linear. Ambas as estratégias fornecem desempenho de tempo constante para pesquisa e inserção sob a suposição de hashing uniforme.

- Symbol Table Applications

    Consideramos várias aplicações de tabelas de símbolos, incluindo conjuntos, clientes de dicionário, clientes de indexação e vetores esparsos.
