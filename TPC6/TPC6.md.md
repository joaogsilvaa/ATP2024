### TPC6

O exercício consiste em desenvolver uma aplicação para a gestão de uma turma de alunos. Cada aluno é representado por uma estrutura que inclui o nome, um
identificador único (ID) e uma lista de três notas (TPC, projeto e teste). A turma, por sua vez, é composta por uma lista de alunos. O objetivo da aplicação
é permitir a gestão desta turma através de um menu interativo com várias funcionalidades.

A aplicação foi implementada com um menu que oferece as seguintes opções: criar uma nova turma, inserir um aluno, listar os alunos da turma, consultar 
informações de um aluno pelo ID, guardar a turma num ficheiro e carregar uma turma a partir de um ficheiro. Cada uma destas operações é realizada por
funções específicas que interagem com a estrutura de dados da turma.

Para resolver o exercício, comecei por implementar funções básicas. A função criar_turma inicializa uma nova turma como uma lista vazia. A função inserir_aluno 
adiciona um novo aluno à turma, construindo a sua estrutura com o nome, ID e notas fornecidos pelo utilizador. A função listar_turma percorre a lista de alunos 
e apresenta as informações de cada um no ecrã. Para consultar os dados de um aluno específico, a função consultar_aluno procura pelo ID fornecido e exibe 
as informações correspondentes.

Além disso, foram implementadas funcionalidades para guardar e carregar a turma num ficheiro. A função guardar_turma salva a lista de alunos num ficheiro 
em formato JSON, permitindo preservar os dados para uso posterior. Já a função carregar_turma lê um ficheiro JSON e reconstrói a lista de alunos.

Por fim, o menu foi estruturado para apresentar as opções ao utilizador de forma clara e cíclica, garantindo que, após cada operação, o utilizador possa
continuar a interagir com a aplicação.