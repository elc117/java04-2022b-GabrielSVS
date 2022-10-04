# java04-2022b-GabrielSVS
java04-2022b-GabrielSVS created by GitHub Classroom

1) **Você consegue identificar alguma redundância nos códigos (dentro de uma mesma classe ou em classes diferentes)?**   
Contém um método get e set para os atributos userId e name, nas classes Student e Professor;


2) **O que aconteceria se fosse necessário armazenar outros atributos sobre estudantes e professores? (por exemplo, CPF, data de nascimento, telefone, etc?)**   
Teria que criar os respectivos métodos get e set (set, caso habilitasse edição) para o novo atributo em cada classe, além de ter que inicializar esse atributo no construtor de cada classe;


3) **O que aconteceria na classe `Laboratory` se tivéssemos outras categorias de membros além de estudantes e professores (técnicos, administradores, etc.)?**   
Criar a ArrayList nova da classe;
Inicializar a ArrayList da nova classe no construtor da classe Laboratory;
Adicionar um método addMember, para adicionar um novo membro na ArrayList desta classe;
Criar um novo loop para adicionar as infos. de cada membro dessa classe na ArrayList<string> contacts, no método getContactInfos(), na classe Laboratory;
Criar um novo loop detector, para comparar o userId procurado com o userId de todos os membros dessa nova classe, no método userExists(), na classe Laboratory;
Adicionar na contagem o tamanho da ArrayList dessa nova classe, no método countMembers(), na classe Laboratory;
