<h2>Desenvolvimento de testes unitários para validar uma API REST de gerenciamento de estoques de cerveja.</h2>



Neste projeto do bootcamp #everis New Talents da **Digital Innovation One**, com base na vídeo aula ministrada pelo **Rodrigo Peleias** o aprendizado foi direcionado a testes unitários de uma API REST para o gerenciamento de estoques de cerveja. Os testes unitários mostram como validar o sistema de gerenciamento de estoques de cerveja, bem como apresenta os principais conceitos e vantagens de criar testes unitários com Junit e Mockito. Além disso mostra como desenvolver funcionalidades da API através da prática do TDD.

Foram abordados os seguintes tópicos:

* Baixar um projeto através do Git para desenvolver os testes unitários. 

* Apresentação conceitual sobre testes: a pirâmide dos tipos de testes, e também a importância de cada tipo de teste durante o ciclo de desenvolvimento.

* Foco nos testes unitários: mostrar porque é importante o desenvolvimento destes tipos de testes como parte do ciclo de desenvolvimento de software.

* Os principais frameworks para testes unitários em Java: Junit, Mockito e Hamcrest. 

* Desenvolvimento de testes unitários para validação de funcionalidades básicas como: criação, listagem, consulta por nome e exclusão de cervejas.

* TDD: "apresentação e exemplo prático em duas funcionalidades importantes: incremento e decremento do número de cervejas no estoque."

  
  
  **Link do Repositório original do Projeto: https://github.com/rpeleias/beer_api_digital_innovation_one **

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Para executar a suíte de testes desenvolvida, basta executar o seguinte comando:

```shell script
mvn clean test
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/beers
```

Para a execução do projeto serão necessários os seguintes pré-requisitos :

* Java 14 ou versões superiores.
* Maven 3.6.3 ou versões superiores.
* Intellij IDEA Community Edition ou sua IDE favorita.
* Controle de versão GIT instalado na máquina.

Abaixo, seguem links sobre tópicos relacionados ao projeto :

* [SDKMan! para gerenciamento e instalação do Java e Maven](https://sdkman.io/)
* [Referência do Intellij IDEA Community, para download](https://www.jetbrains.com/idea/download)
* [Palheta de atalhos de comandos do Intellij](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
* [Site oficial do Spring](https://spring.io/)
* [Site oficial JUnit 5](https://junit.org/junit5/docs/current/user-guide/)
* [Site oficial Mockito](https://site.mockito.org/)
* [Site oficial Hamcrest](http://hamcrest.org/JavaHamcrest/)
* [Referências - testes em geral com o Spring Boot](https://www.baeldung.com/spring-boot-testing)
* [Referência para o padrão arquitetural REST](https://restfulapi.net/)
* [Referência pirâmide de testes - Martin Fowler](https://martinfowler.com/articles/practical-test-pyramid.html#TheImportanceOftestAutomation)

**MADS1974**



