# PegasusProject
O projeto Pegasus consiste em analisar o comportamento dos alunos e os caminhos que os mesmos trilham ao interagirem com a plataforma LoP.

## Métodos utilizados
A base de dados veio da plataforma LoP. De 2017.2 à 2019.1. 

Foi realizado um tratamento a fim de selecionar os dados com as submissões que sejam certas e que contenham questões diferentes. Se selecionada as 18 primeiras semanas das 21 possíveis em um semestre, já que nas 3 últimas os estudantes estão focados em desenvolver o projeto final da disciplina, e o target que foi a situação final dele na disciplina, aprovado ou reprovado. Para criar a idéia de progresso durante as semanas eu quebrei em 18 linhas, na qual a primeira terá apenas a 1ª semana, a segunda linha terá a 1ª e a 2ª, e assim por diante, até completar as 18 semanas.

## Self-Organzing Maps (SOM)
A SOM é uma rede neural artificial (RNA) do tipo não-supervisionada, que foi proposta por Kohenen em 1982, ela busca encontrar nas entradas similaridade aos neurônios sorteados - aleatóriamente, assim agrupando os com entradas parecidas. Isso a diferencia das outras RNA, em que a maioria é o método de competição é a de menor erros encontradaos, já a rede SOM utiliza o método de competição. A rede SOM miniliza o problema das multi-dimensionalidades, conseguindo fazer com que um problema que tenha n-dimensões vire um problema em 2 dimensões (2D).

## Implementação
Como eu realizei a quebra em 18 linhas, eu consigo fazer a evolução do aluno dentro de um mapa 2D. Utilizando a teoria dos grafos e a biblioteca NetworkX, que aplica esse tipo de teoria, eu consigo plotar a rota que o estudante tomou dentro da disciplina. 

Com isso, com mínimo de semanas possíveis já dá para mostrar ao estudante que ele pode estar seguindo a trajetória que outros estudantes também seguiram quando acabaram reprovando.



**Este projeto foi superivisionado pelo professor Dr. Orivaldo Vieira.**
