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
<h1></h1>
<h2>Projeto 1: 1º Semestre de 2021</h2>
<h3> Parceiro academico </h3>
Projeto Integrador, Fatec Prof. Jessen Vidal - 2021. 1° Semestre
Cliente Interno: Profº Fabiano Sabah</a>
<h3> Visão do Projeto </h3>
Com o intuito de proporcionar aos estudantes uma maneira mais eficiente e organizada de gerenciar suas atividades acadêmicas e se manterem informados, foi desenvolvida a Athena - uma assistente pessoal de estudos. O que a torna especial é a sua capacidade de integrar diversas ferramentas úteis em um só lugar.<br>
A ideia inicial do projeto era construir uma ferramenta capaz de auxiliar estudantes em suas rotinas, com a principal ideia de ser inclusiva para pessoas com deficiência visual. 
<br>
<details>
<summary>Mostrar backlog do Produto</summary>
<img src="https://user-images.githubusercontent.com/81486915/229939643-891abdaa-e090-49d2-8dd3-df5d5407d696.png">
</details>
<h3> Tecnologias utilizadas </h3>
- Python
- pydub
- Tkinter
- SpeechRecognition
- PyAudio
- pyttsx3
- SQLite3
- ismtplib
- email.mime.text
<h2> PYTHON </h2>
<h3> Contribuições pessoais </h3>
Estruturei com a Linguagem Python a base de como seria o projeto. Onde atuei fortemente no reconhecimento de voz para texto com o SpeechRecognition e PyAudio.
Parte essa importante no projeto onde era o Core da aplicação. Parte da dificuldade do projeto seriam criar dois tipos de motores principais, onde o primeiro motor precisa entender um texto e transforma-lo em voz e no segundo motor o caminho inverso, transformar voz em texto.


<details>
<summary>Mostrar exemplo</summary>
<img src="https://user-images.githubusercontent.com/81486915/229943884-d166a94f-bc59-4013-8f06-a3209355d565.png"/>
   ↳ No código acima podemos notar onde foi definido a função de fala, passando um texto como argumento. Essa função não retorna nada apenas chama a Engine.
</details>

Também atuei na lógica de programação e como funciona a estrutura de um software simples. 
Estruturei a parte funcional de retorno da assistente pessoal, ou seja o reconhecimento de algumas palavras pré setadas em memória. Assim seguindo e orientando o usuário a seguir um fluxo de conversa. 

<details>
<summary>Mostrar exemplo</summary>
<img src="https://user-images.githubusercontent.com/81486915/235800030-f209a0ed-91ec-48c9-be13-b7578c53081d.png"/>
  ↳ O código mostra alguns exemplos pré setados de comunicações com a assistente de voz. Essas palavras são armazenadas em memória ao momento que executar a aplicação.
 Trata-se também de uma função em Python 3 que é chamada no runner.
 </details>

<h3> Aprendizados Efetivos HS </h3>

Neste projeto que fomos desafiados pela FATEC, pude entender como funciona o inicio do SCRUM e como desenvolver um software com a implementação da lógica de programação.

Dentro alguns conhecimentos técnicos, posso destacar: 

- Lógica de programação o que é e como funciona Algoritmos.
- Python 3 Utilizando python para criar uma aplicação.
- Banco de dados em memória e como funciona o armazenamento simples de dados. 
- Bibliotecas e como utilizar estruturas criadas por outros desenvolvedores.
- Funções o que é e como retornar sua função.

<details>
<summary>Exemplo de import</summary>
<img src="https://user-images.githubusercontent.com/81486915/235803193-5a33c858-79c7-4090-b68d-101b0bc0a4f3.png"/>
 
 ↳ O código acima mostra como funciona os import na linguagem Python (algumas bibliotecas precisam do comando pip install + nome da lib)
 </details>
 
 <details>
<summary>Exemplo de funções</summary>
 <img src="https://user-images.githubusercontent.com/81486915/235803492-c3c1b6e3-4fbb-4d58-8b56-b04960cd3620.png"/>
 
  ↳ No exemplo podemos ver como criar uma função e o que ela retorna. Também podemos passar parametros para essa função ou não. Em algumas funções utilizamos as bibliotecas que importamos anteriormente
 </details>
 
<details>
<summary>Exemplo do run utilizando funções e bibliotecas</summary>
<img src="https://user-images.githubusercontent.com/81486915/235803537-7a807b85-7a43-4424-8a74-01e5843d42f3.png"/>
 
  ↳ No código acima é possível notar o run, a utilização de algumas bibliotecas e funções.
 </details>

<h2>Projeto 4: 2º Semestre de 2022</h2>
<h3> Parceiro academico </h3>
Projeto Integrador, Fatec Prof. Jessen Vidal - 2022. 4° Semestre
Cliente: <a href="https://www.subiter.com/">Subiter</a>

<br>
<p align="center">
 <img src="https://user-images.githubusercontent.com/80851038/190831621-96d01aab-af9f-4b9b-a7c5-9e6419d287bb.jpeg" width="110"/>
</p>

<h3> Visão do Projeto </h3>
Temos um desafio de sincronização dos dados administrativos, financeiros e operacionais referentes aos serviços prestados pela empresa. A falta de organização dos dados acarreta lentidão para atender chamados, e confusão na interpretação dos indicadores comerciais e financeiros.
<h3>Solução</h3>

aqui vai as prints do projeto

Desenvolvemos uma plataforma web que organiza todos os dados referentes aos serviços prestados pela empresa, de forma interpretada, cujo o principal objetivo é criar chamados e agendamentos conforme as necessidades do cliente e solucioná-los de forma ponta a ponta entre a relação do cliente com o suporte e, suporte com a do administrador que, trabalha na criação e sincronização dos dados em um único lugar.
<h3> Contribuições pessoais </h3>
Neste projeto atuei como desenvolvedor arquiteto do back-end, onde documentei a API com Swagger, configurei o Oracle Cloud como BD em nuvem,Segurança da API com niveis de acesso com o Spring Security + JWT, inicei a parte de Devops com o Deploy da aplicação, desenvolvi API'com relacionamentoss complexos utilizando o Spring Boot 2.7 e apliquei alguns padrões de projetos a fim de facilitar a manutenção no código e desacoplar algumas classes com interfaces.<br>

<details>
<summary>Mostrar/recolher</summary>
<img src="https://github.com/IgorRibeiro-S/bertoti/assets/81486915/f1426130-4552-42aa-a5dd-a3935f5e45fa"/><br>
  ↳ Classes de configuração de segurança SpringSecurity + JWT. Classes responsáveis por criar o token de segurançã com expiração de 60 minutos, com o token gerado é possível saber o tipo de "ROLE" do usuário e que autorização ele possuí. Sendo Autenticação e Autorização. 
</details>

![image](https://github.com/IgorRibeiro-S/bertoti/assets/81486915/a8b6d46d-77cf-48f6-a2c5-ba0e99c02ca0)
Configuração Wallet Oracle Cloud para BD em nuvem

![image](https://github.com/IgorRibeiro-S/bertoti/assets/81486915/dc056021-a290-49a7-bead-f31f75ab8277)
Exemplo da Classe Request que envolve diversos relacionamentos complexos

![image](https://github.com/IgorRibeiro-S/bertoti/assets/81486915/b7941c3a-c58c-41cc-80c2-caf4e3138565)
Exemplo do deploy da aplicação na plataforma do Heroku

![image](https://github.com/IgorRibeiro-S/bertoti/assets/81486915/c610b2da-cbf5-415d-8732-022ca7903385)
Classe de configuração da documentação da API com Swagger






