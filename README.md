# Kotlin-Forum-Alura
 
Nós trabalhamos no fórum da Alura, criando a API REST do fórum e iniciamos o projeto do zero. Aprendemos a criar o projeto utilizando o site start.spring.io, que é o Spring Initializer, e vimos como configurar nosso projeto, adicionar o Kotlin, adicionar as dependências do Maven.

Posteriormente, aprendemos a importar esse projeto no IntelliJ e começamos a trabalhar no projeto. Criamos nossos controladores, as classes de domínio, representando os recursos de nossa API. Focamos bastante na parte do tópico, no controller relacionado ao tópico, com esse recurso de nossa API.

Aprendemos como criar um controller e como ele funciona. Criamos os métodos para fazer as manipulações do recurso. Mapeamos as URIs e os métodos, get, post, put e delete, para implementar o CRUD completo do tópico.

Aprendemos a trabalhar com uma classe de serviço para isolar as lógicas, as validações e as regras de negócio, tudo na classe de serviço, evitando deixar isso no controller, que é uma boa prática bastante utilizada no mercado.

Vimos como utilizar DTOs (Data Transfer Objects) para representar os dados que chegam e saem de nossa API, o que oferece mais flexibilidade e evita a exposição desnecessária de dados na API. Também utilizamos mappers, pois precisamos fazer a conversão de DTO para classe de domínio e vice-versa. Criamos as classes mappers, que também é um padrão bastante comum no mercado, para realizar essa conversão entre esses dois tipos de objetos.

Focamos nas boas práticas do modelo REST, questão de recursos, URI, verbos HTTP, códigos HTTP. Ajustamos para utilizar corretamente os códigos do protocolo HTTP.

Por fim, fizemos o tratamento de erro na nossa API, quando ocorrem erros 404, 500 e erros de validação do Bean Validation. Aprendemos a usar o Bean Validation para fazer validação e os testes da API, utilizando o Postman.

    Criação do projeto via Spring Initializer
    Importar projeto no IntelliJ
    Criação de Controller
    CRUD de tópicos
    Criação de classe Service
    Utilização de DTOs para representar dados da API
    Utilização de Mappers para conversão DTO<->Domínio
    Boas práticas do REST
    Tratamentos de erros na API