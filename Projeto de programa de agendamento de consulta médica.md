Esse exercício aqui foi produzido a partir de uma aula sobre enumerações e composições de classes java. A princípio é necessário compreender a situação dada para qualquer
atividade de desenvolvimento de programas de computadores. Desse modo, podemos expressar um modelo de consulta médica sob conceitos de progamação orientada à objetos tais
como: classes e suas relações de negócio, enumerações, métodos e manipulação de classes Date, DateTime e mais uma vasta quantidade de recursos que a linguagem Java nos dis
-ponibiliza.

Um médico pode realizar várias consultas e um paciente também pode ter várias consultas. Associação de muitos para muitos. Podemos associar médico e paciente através de uma
terceira classe, a classe Consulta, que é dita uma Classe Associativa. Para isso, foi necessário a utilização de classes que oferecem recursos de estrutura de dados para 
armazenar objetos do classe consulta que possui atributos principais Objetos da classe Medico e da classe paciente. Nota-se que na classe Consulta possui um método chamado
Receita, que permite que o médico(usuário) preescreva uma receita para o paciente instanciado. 

Já na classe Clinica, onde ocorre a leitrua de dados para a execução da consulta, utilizei a classe Date para obter a "Date" para obter a data e a hora da consulta. Primeiramente
instanciei "DateTimeFormatter" que é um classe onde o seu objeto oferece métodos que formatem o tipo do dado inserido para um específico( nesse caso utilizei o padrão "dd/MM/yyyy HH:mm").
No entanto, tal prática requer o recurso throws "ParseException" que irá tratar uma exceção causada por esse modelo de leitura de datas.


