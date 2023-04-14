
Neste projeto, vamos escrever uma API onde usaremos um ORM -
um mapeador de banco relacional. Sequelize é o nome do ORM que usaremos.


------ ORM Sequelize: Já imaginou ter que escrever todas as querys 
de um banco de dados? Pensando nisso ferramentas como o ORM (Object-Relational Mapping) 
funcionam para facilitar o cotidiano de desenvolvimento. Dessa forma o Sequelize suporta diversos 
bancos de dados relacionais como PostgreSQL, MySQL, SQLite e MSSQL. Com o Sequelize, é 
possível mapear objetos do JavaScript para tabelas do banco de dados e realizar operações 
de CRUD (Create, Read, Update, Delete) utilizando apenas JavaScript, sem a necessidade 
de escrever queries em SQL.

O Sequelize também possui uma ferramenta de linha de comando, que chamamos de 
CLI (Command Line Interface), que pode ser usada para criar um banco de dados, gerar modelos, 
migrações e seeders, dentre outras tarefas. 


------ Migração com ORM: alterações incrementais e rastreáveis no banco. A migração com ORM 
permite voltar o estado da nossa tabela a um estado anterior, se precisar. É uma segurança para 
você rastrear as alterações feitas no banco. 


------ Modelo MVC: O modelo MVC é um padrão de arquitetura de software que separa os dados, 
a lógica de negócios e a interface do usuário em três componentes distintos: Model, View e 
Controller (Modelo, Visualização e Controlador, em português). O modelo representa os dados e 
a lógica de negócios da aplicação, e é responsável por armazenar, gerenciar e manipular os dados, 
além de fornecer métodos para acessá-los e modificá-los.
A visão (ou view) é responsável pela apresentação dos dados ao usuário, sendo a interface gráfica ou textual.
O controlador é responsável por gerenciar a comunicação entre o modelo e a visão, recebendo 
entradas do usuário e coordenando as ações necessárias para atualizar o modelo e a visão de 
acordo com as interações do usuário.
O padrão de arquitetura MVC é amplamente utilizado em sistemas de software, especialmente em aplicações web e desktop.