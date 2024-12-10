<h1 align="center"> <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/> <img src="https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot"/> <img src="https://img.shields.io/badge/Junit5-25A162?style=for-the-badge&logo=junit5&logoColor=white"/> <img src="https://img.shields.io/badge/apache_maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white"/> <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
</h1>

# <g-emoji class="g-emoji" alias="computer" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4bb.png">💻</g-emoji>Crud - Clínica Odontológica " Clean Odonto"

# Clean Odonto

## Descrição

Clean Odonto é um sistema de gerenciamento para uma clínica odontológica, permitindo administração de pacientes, dentistas e consultas. Além disso, o sistema conta com autenticação e autorização para gerenciar o acesso aos diferentes recursos com segurança integrada.

## Links Importantes

- **Documentação da API**: [Swagger](http://localhost:8080/api-clean/swagger-ui/index.html)
- **Banco de Dados H2**: [Console H2](http://localhost:8080/api-clean/h2-console)

## Objetivo

Implementar um sistema para administrar a reserva e marcação de consultas em uma clínica odontológica, com as seguintes funcionalidades principais:

## Funcionalidades

### Administração de Dados Odontológicos

- Adicionar e modificar os dados dos dentistas.
- Registrar nome, sobrenome e matrícula de cadastro.

### Administração de Pacientes

- Registrar, modificar e excluir pacientes.
- Armazenar: nome, sobrenome, endereço, RG, data de alta.

### Login

- Validar a entrada no sistema com nome de usuário e senha.
- Permitir que qualquer usuário logado registre consultas.
- Apenas usuários com função de administração podem gerenciar dentistas e pacientes.

### Registrar Consultas

- Atribuir pacientes a consultas com dentistas em datas e horários definidos.

## Estrutura do Sistema

O sistema foi desenvolvido em camadas, seguindo os princípios de boas práticas de design:

1. **Camada de Entidade de Negócios**: Classes Java modeladas segundo o paradigma de orientação a objetos.
2. **Camada de Acesso a Dados (Repositório)**: Classes para interação com o banco de dados.
3. **Camada de Dados (Banco de Dados)**: Banco relacional modelado com H2 para praticidade.
4. **Camada de Negócio**: Classes de serviço para desacoplar a lógica de negócio da camada de acesso aos dados.
5. **Camada de Apresentação**: Desenvolvida com Spring Boot MVC e frameworks como HTML+JavaScript ou React para a visualização.
6. **Tratamento de Exceções e Testes Unitários**: Captura de exceções e testes para garantir qualidade e robustez.

## Implementação

O sistema conta com os seguintes componentes principais:

- **Controllers**: Gerenciam as requisições HTTP.
- **Repositories**: Manipulação de dados no banco.
- **Exceptions**: Tratamento de erros e exceções.
- **Entities DTO**: Representações dos dados.
- **Services**: Lógica de negócio.

## Requerimentos Técnicos

- **Java**
- **JUnit 5**
- **Maven**
- **Spring Boot**
- **H2 Database**
- **Mockito**
- **SpringDoc**

