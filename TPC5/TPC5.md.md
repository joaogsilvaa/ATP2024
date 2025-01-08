### TPC5

O exercício consiste em desenvolver uma aplicação para gerir salas de cinema num centro comercial. Cada sala possui uma lotação máxima, uma lista de 
bilhetes vendidos (identificados por números inteiros correspondentes aos lugares ocupados) e o nome do filme exibido. O objetivo principal é implementar
funcionalidades para gerenciar estas salas e interagir com o utilizador através de um menu.

O modelo proposto define que um cinema é composto por uma lista de salas, sendo cada sala caracterizada pelo número total de lugares, a lista de lugares 
ocupados e o nome do filme exibido. Com base neste modelo, foram desenvolvidas várias funções para desempenhar tarefas específicas, como listar os filmes
em exibição, verificar a disponibilidade de lugares, vender bilhetes, listar a disponibilidade de lugares em cada sala e inserir novas salas no sistema. 
Além disso, foi implementado um menu de interface para facilitar a interação com o utilizador.

Para resolver o exercício, comecei por implementar as funções principais. A função listar exibe todos os filmes atualmente em exibição nas salas. A função
disponivel verifica se um determinado lugar está disponível numa sala específica com base no filme exibido. A função vendebilhete regista a venda de um lugar
ao atualizar a lista de lugares ocupados. A função listardisponibilidades apresenta o número de lugares disponíveis em cada sala e o respetivo filme 
em exibição. Por fim, a função inserirSala permite adicionar uma nova sala ao cinema, assegurando que não existe duplicação de filmes.

Depois de definir estas funcionalidades, construí um menu interativo para permitir ao utilizador executar as diferentes operações de forma intuitiva. 
O menu oferece opções para inserir novas salas, listar os filmes em exibição, verificar a disponibilidade de lugares, vender bilhetes, listar as 
disponibilidades de cada sala e sair do programa. Cada opção é processada com base nas funções implementadas, permitindo um controlo eficaz do sistema 
de gestão do cinema.