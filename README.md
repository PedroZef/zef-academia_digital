Conhecendo o Projeto Spring Data JPA na Prática 
Sejam bem-vindos ao projeto de LAB Conhecendo o Projeto Spring Data JPA na Prática oferecido gratuitamente pela plataforma de cursos online <a href="https://dio.me/"><strong> Digital Innovation One

## - Objetivo do Projeto
Ao final deste projeto, o Dev irá conhecer os principais conceitos de mapeamento objeto relacional (ORM) usando o Spring Data JPA. Para isso, uma API RESTful será desenvolvida com ênfase na modelagem de suas entidades, no domínio de uma academia de ginástica.

🛑 Pré-requistos

- [x] Fundamentos do Spring Boot

- [x] Noções de SQL

 ## - Apresentação do Projeto Base 
    Configuração do banco de dados (SGBD  em PostgreSQL em Aplicando as em annotations em Execução do fluxo back-end: em Controller - Service - Repository em Validação em Hibernate Validator em Consultas Avançadas  em Derived Query - Native Query.

🛠 Tecnologias Utilizadas

    - IDE IntelliJ
    - Java 11
    - Maven   
    - Spring Web
    - Spring Data JPA
    - PostgreSQL Driver
    - Hibernate Validator
    - H2
    - Lombok
    - Postman

<a href="https://strn.com.br/artigos/2018/12/11/todas-as-anota%C3%A7%C3%B5es-do-jpa-anota%C3%A7%C3%B5es-de-mapeamento/" ></a> Anotações de Mapeamento 

### @Entity
Usada para especificar que a classe anotada atualmente representa um tipo de entidade.

### @Table
Usada para especificar a tabela principal da entidade atualmente anotada.

### @Id
Especifica o identificador da entidade. Uma entidade deve sempre ter um atributo identificado.

<strong>@GeneratedValue
Especifica que o valor do identificador de entidade é gerado automaticamente.

### @Column
Usada para especificar o mapeamento entre um atributo de entidade básico e a coluna da tabela de banco de dados.

### @JoinColumn
Usada para especificar a coluna FOREIGN KEY. Indica que a entidade é a responsável pelo relacionamento.

#### @OneToMany
Usada para especificar um relacionamento de banco de dados um-para-muitos.

### @OneToOne
Usada para especificar um relacionamento de banco de dados um-para-um.

### @ManyToOne
Usada para especificar um relacionamento de banco de dados muitos-para-um.

### cascade
Realizar operações em cascata só faz sentido em relacionamentos Pai Filho.

### mappedBy
Indica qual é o lado inverso ou não dominante da relação.

## 🔗 Links Úteis
<a href="https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.6.1&packaging=jar&jvmVersion=11&groupId=me.dio.academia&artifactId=academia-digital&name=academia-digital&description=Tutorial%20API%20RESTful%20modelando%20sistema%20de%20academia%20de%20gin%C3%A1stica&packageName=me.dio.academia.digital&dependencies=web,data-jpa,postgresql,validation,lombok">Spring Initializr</a>
<a href="https://docs.spring.io/spring-boot/docs/2.0.x/reference/html/common-application-properties.html">Common application properties</a>
<a href="https://docs.spring.io/spring-data/jpa/docs/current/reference/html/#jpa.repositories">Spring Data JPA - Reference Documentation</a>

Este repositório foi criado para fins de estudo por Camila Cavalcante, que todos os méritos sejam dados.
