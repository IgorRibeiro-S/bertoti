<h1> Igor Ribeiro Silva </h1>
<h2> Introdução </h2>

Olá, seja bem-vindo. Sou o Igor Ribeiro, estudante de Banco de Dados pela FATEC Prof. Jessen Vidal.

<img src="https://user-images.githubusercontent.com/81486915/204921113-a6501f99-91a7-4bff-8d98-9576f5fbe99c.jpg">


<h3> Principais Conhecimentos </h3>

<b>Java</b>
Meu primeiro contato com a Linguagem foi em 2021, com aulas na FATEC. Atualmente utilizo e atuo com a Linguagem Java(8 e 11), com forte atuação no Back-end, conhcimento sólido no Java (8 e 11)  como : Expresssões lambda, Padrões de projetos, Java persistence, web services, micro services.
Também possuo conhecimento em alguns Frameworks da linguagem: Spring, SpringBoot, Quarkus, JavaFX e Hibernate ORM.

<h2>Projeto 3: 1º Semestre de 2022</h2>
<h3> Parceiro academico </h3>
Projeto Integrador, Fatec Prof. Jessen Vidal - 2022. 3° Semestre
Cliente: <a href="https://www.midall.com.br/">MidAll</a>

<br><p>
 <a href="https://www.midall.com.br/"><img src="https://user-images.githubusercontent.com/80851038/163725778-498ec2e9-e8eb-45cf-a586-848e5bb1dd97.png" width="110"/></a>
</p>

<h3> Visão do Projeto </h3>

"Temos um problema para criação de **promoções em um Ecommerce**. Precisamos de uma solução inteligente onde, as mecânicas das promoções sejam feitas de forma flexível e de rápida atualização no sistema." - MidAll.

A ideia é criar um mini motor de regras com uma interface onde as regras das promoções possam ser cadastradas e aplicadas no momento que os itens forem para o carrinho de compras.

<details>
<summary>Mostrar exemplo</summary>
<img src="https://user-images.githubusercontent.com/81486915/202873966-c6a51cc0-7cd5-419c-8c46-71edddff880a.jpg">
<img src="https://user-images.githubusercontent.com/81486915/202873967-bac5b668-10ce-4db0-913e-f74d0fb02b18.jpg">
<img src="https://user-images.githubusercontent.com/81486915/202873968-b1c1e222-fd5b-4bcb-9d2e-e78c81861b75.jpg">
<img src="https://user-images.githubusercontent.com/81486915/202873969-11fead79-03e9-407c-983c-6cc6ab02a58e.jpg">
</details>

<h3> Tecnologias utilizadas </h3>

- Linguagem Java;
- Banco de Dados Relacional;
- Documentações.

- Quarkus
- JQuery
- PostgrSQL
- JavaScript
- Docker
- ORM
- Maven

<h3><b>QUARKUS</h3></b>

Tive meu primeiro contato com um Framework back-end com o Quarkus, sendo voltado para Web services e Microservices, trata-se de uma tecnologia forte e confiável, tendo grande impacto positivo no projeto. Com o Quarkus, fui capaz de criar e implementar conceitos dos padrões de projetos, como inversão de controle e Injeção de dependência. 
É uma tecnoclogia que possui o hot reload no back-end, ou seja, a cada alteração no projeto ele restarta a aplicação sem a necessidade de uma nova compilação, ajudando a encontrar presença de bugs e otimizando o tempo.


<h3> Contribuições pessoais </h3>

Fiz parte do time de Back-end, onde participei ativamente na criação dos CRUDs da API. Organizei os packages da aplicação e a estrutura dos códigos com: 
- RESOURCES;
- CONTROLLERS;
- ENTIDADES, etc...

<details>
<summary>Mostrar exemplo</summary>
<img src="https://user-images.githubusercontent.com/81486915/191622260-1c4437f8-0fc9-4a55-93bd-25b381a55286.png"><br>
↳ Diretório organizado conforme convenção da linguagem. Contendo os repositories, resources(controllers), services e entities. 
</details>

Fui o responsável por criar e desenvolver a entidade, repository, resource, service e DTO do Produto, onde também foi criado a lógico de validação de produto no estoque: 

<details>
<summary>Mostrar exemplo</summary>
<img src="https://user-images.githubusercontent.com/81486915/191624904-1b53273a-a2f2-45af-bafc-cc3c16c00a34.png"><br>
<img src="https://user-images.githubusercontent.com/81486915/191624991-8470c457-d2b3-430e-9bd0-ee238b66ba7f.png"><br>
 ↳ Os códigos acima tratam da entidade Produto e Método onde é validado a lógica de verificar a disponibilidade do produto. A Classe produto extende o PanacheEntity, camada extra da ORM (Object-Relational Mapping) que faz o mapeamento relacional com o banco de dados. No método setStatusProd é criado uma lógica onde recebe uma chamada nos Services, ao criar um Produto é realizado uma transação no banco de dados que informa a disponibilidade do produto como True, sendo possível altera-la de acordo com a regra de negócio.
</details>

Também fui o responsável pela criação do acesso ao Banco de Dados com a anotação @ApplicationScoped, sendo utilizado pelo service com injeção de dependência.

<details>
<summary>Mostrar exemplo</summary>
<img src="https://user-images.githubusercontent.com/81486915/196818992-35724316-ccbc-43be-a67e-146cd524d21c.png"><br>
 ↳ Código do Repository da entidade Produto, o código faz o processo de GET e POST na conexão com o banco de dados pela camada do panache entity. Classe essa responsável das Querys e transações no banco de dados.
</details>

<details>
<summary>Mostrar exemplo</summary>
<img src="https://user-images.githubusercontent.com/81486915/196819156-95a9dbcf-0372-4bf5-a2ef-64096daf32cc.png"><br>
 ↳ Código do ProdutoService onde é realizado a camada de Service da entidade Produto, sendo feito a injeção de depêndencia do repository. Nesta classe é realizado os métodos públicos, cadastrar, atualizar e deletar.
</details>


Utilizei padrões, técnicas e boas práticas a fim de desenvolver um codigo limpo e de fácil manutenção.

<h3> Aprendizados Efetivos HS </h3>

O projeto proposto pela empresa Midall foi o primeiro sistema web com o qual trabalhei. Em seu desenvolvimento, obtive meu primeiro contato com conceitos bases para todo profissional desenvolvedor de software. Abaixo estão algumas tecnologias aprendidas no semestre:

protocolo HTTP;
Requisição GET, POST, PUT, DELETE;
- O que é um JSON e como ele funciona na comunicação de sistemas web;
- O que é um framework web e qual sua utilidade na construção de sistemas;
- O que é e como funciona a conteinerização;
<details>
<summary>Mostrar exemplo</summary>
<img src="https://user-images.githubusercontent.com/81486915/202873593-38a6e11f-0380-4949-9052-d156aeaee534.png"><br>
 ↳ Classe ProdutoResource que faz parte da camada dos Controllers, com os métodos HTTP: GET, POST, DELETE e UPDATE. Também fazendo a injeção de dependência da classe Service. Também é utilizado na classe as anotações do Quarkus (PUT, GET, DELETE E POST) para os métodos que foram injetos do Service.
</details>
 
Nesse projeto atuei como Scrum Master e Dev, onde pude aprender na prática como a metodologia ágil (Scrum) ajuda e organiza o projeto como um todo. Na função como dev tive aprender matérias que foram essenciais para o desenvolvimento do projeto, como: Estrutura de dados, Framework Quarkus e Programação em BD. Aprendi como estruturar um back-end com códigos limpos e organizados, fazendo uso das convenções adotadas pela linguagem Java. 

Uma prioridade que foi pensada a todo momento, foi na experiência do usuário, tanto no back-end como no front-end. Por se tratar de um e-commerce era importante criar uma ferramenta que fosse de fácil utilização, tanto para o Operador quanto para o Usuário final. 

Alguns pontos importantes de aprendizado nesse semestre foram:

* Criação de uma API REST - HTTP
* Consumo de API's externas
* Dados relacionais
* conteinerização
* Organização do diretório de arquivos






