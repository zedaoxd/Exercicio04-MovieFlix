# Exercício 04 - Movie Flix

## Sobre o projeto
Este é o quarto desafio do **Bootcamp Spring** da [DevSuperior](https://devsuperior.com.br/cursos) cuja aulas estão sendo ministradas pelo professor [Nelio Alves](https://www.linkedin.com/in/nelio-alves/?originalSubdomain=br).
O sistema MovieFlix consiste em um banco de filmes, os quais podem ser listados e avaliados pelos usuários. Usuários podem ser visitantes (VISITOR) e membros (MEMBER).

Neste exercício foi proposto que implementassemos as funcionalidades para que os testes de validação, segurança e autorização passassem passasem, e também implementar todo modelo ORM.

### Etapas implementadas
 - Implementar o modelo conceitual proposto, com seed do banco de dados.
 - Incluir a infraestrutura de exceções, validação e segurança ao projeto.
 - Implementar o endpoint (GET /users/profile).
 - Seed do banco contendo dois usuários:
   - Usuário somente com perfil VISITOR:
   
     email: bob@gmail.com
   
     senha: 123456
   
   - Usuário com perfil MEMBER:
   
     email: ana@gmail.com
   
     senha: 123456



## Modelo Conceitual
![Modelo Conceitual](https://user-images.githubusercontent.com/55067151/194101985-200e199a-c9e0-4705-8eb8-fdc050ab4886.png)

## Tecnologias utilizadas
- Java
- Spring Boot
- JPA / Hibernate
- Maven

## Como executar o projeto

Pré-requisitos: Java 11
- Clone o projeto
```bash
# clonar repositório
git clone https://github.com/zedaoxd/Exercicio04-MovieFlix.git
```
- Importe na sua IDE Java
- Clique em Run Tests / Play

## Autor

[Bruno Lessa Ferraz](https://www.linkedin.com/in/bruno-lessa-ferraz/)

