### TPC8

O primeiro exercício tem como objetivo identificar as diferenças entre duas listas, ou seja, os elementos que são exclusivos de cada uma. 
Para resolver este problema, foram usadas listas em compreensão, percorrendo os elementos de ambas as listas e selecionando aqueles que
não estão presentes na outra. O resultado final é a combinação dessas diferenças.

O segundo exercício foca-se na extração de palavras com mais de três letras a partir de um texto dado. O texto é dividido em palavras 
individuais utilizando o método split, e, em seguida, são filtradas as palavras com comprimento superior a três caracteres através de uma 
lista em compreensão.

No terceiro exercício, o objetivo é criar uma lista de tuplos a partir de uma lista de palavras. Cada tuplo contém o índice e a palavra
correspondente. A resolução utiliza uma combinação do método index e uma lista em compreensão para formar os tuplos desejados.

O quarto exercício implementa uma função chamada strCount, que conta o número de vezes que uma substring aparece numa string maior. A solução
é baseada numa estrutura de ciclo while que percorre a string e verifica, a cada iteração, se a substring aparece na posição atual.
Quando a substring é encontrada, o índice avança pelo comprimento da substring, acumulando a contagem.

No quinto exercício, o objetivo é calcular o produto dos três menores números de uma lista. Para isso, a lista é ordenada em ordem crescente,
e o produto dos três primeiros elementos é calculado diretamente. O resultado é então devolvido.

O sexto exercício tem como objetivo reduzir um número inteiro positivo a um único dígito, somando repetidamente os seus dígitos até que o 
resultado seja inferior a 10. A solução utiliza dois ciclos while: o primeiro controla o processo de redução enquanto o número for maior 
ou igual a 10, e o segundo soma os dígitos do número dividindo-o sucessivamente. O resultado final é o dígito único obtido.

O sétimo exercício foca-se em determinar o índice de uma substring dentro de uma string maior, semelhante ao método index em Python, mas 
com o tratamento de casos em que a substring não está presente. A solução verifica se a substring existe na string e, em caso positivo,
devolve o índice onde ela começa, caso contrário devolve -1.

O oitavo exercício introduz uma rede social representada como uma lista de dicionários, onde cada dicionário representa um post com 
informações como conteúdo, autor e comentários. Com base nesta estrutura, são implementadas várias funções para realizar diferentes 
operações. Uma delas, por exemplo, calcula o número total de posts na rede social, simplesmente percorrendo a lista e acumulando a contagem.

Outra função, também relacionada à rede social, conta quantos posts foram feitos por um determinado autor. Para isso, a lista de posts é 
percorrida, e os posts cujo autor coincide com o especificado são contabilizados. Há ainda uma função que devolve uma lista ordenada de 
autores únicos, garantindo que cada autor apareça apenas uma vez.

Além disso, foram desenvolvidas funções para adicionar novos posts, removê-los com base no seu identificador e listar os posts agrupados 
por autor. Para adicionar um post, cria-se um novo dicionário com os dados fornecidos e um identificador único, que é gerado com base no 
número total de posts já existentes. A remoção de um post é feita percorrendo a lista e eliminando o elemento que corresponde ao 
identificador especificado.

Por fim, foi implementada uma função que retorna os posts comentados por um autor específico. A solução percorre os comentários de cada post
e verifica se o autor do comentário coincide com o autor especificado, acumulando os posts que atendem a essa condição.

Esses exercícios exploram diversas técnicas de manipulação de listas, dicionários e strings em Python, aplicadas a contextos práticos 
como processamento de números, análise de texto e gestão de dados de uma rede social.