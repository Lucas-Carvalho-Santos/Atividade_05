
# ✅ Testes Unitários e Mocking em Spring Boot

Este projeto tem como objetivo a implementação e validação de testes unitários para o controlador de usuários em uma aplicação Spring Boot, utilizando **JUnit 5** e **Mockito**.

---

## 🎯 Objetivo

Implementar testes unitários eficazes para os endpoints do controlador de usuários, garantindo a confiabilidade e a robustez da aplicação por meio de simulações (mocking) de dependências.

---

## ⚙️ Tecnologias Utilizadas

- Java 11 ou superior  
- Spring Boot  
- Spring Web  
- Spring Data JPA  
- Spring DevTools  
- MariaDB  
- JUnit 5  
- Mockito  

---

## 📦 Configuração do Ambiente

1. Certifique-se de que o projeto está configurado com as seguintes dependências no `pom.xml`:
   - `spring-boot-starter-web`
   - `spring-boot-starter-data-jpa`
   - `mariadb-java-client`
   - `spring-boot-devtools`
   - `spring-boot-starter-test` (inclui JUnit 5 e Mockito)

2. Configure o banco de dados MariaDB corretamente no arquivo `application.properties`.

---

## 🧪 Execução dos Testes

Para rodar os testes:

```bash
./mvnw test
```

Todos os testes devem ser executados e aprovados. Caso algum falhe, analise a causa e aplique as correções necessárias no código da aplicação ou no próprio teste.

---

## 📝 Relatório de Testes

- Testes foram criados para os principais métodos do controlador de usuários.
- As dependências como `UserService` foram simuladas com **Mockito** para isolar o comportamento do controlador.
- Todos os testes foram executados com sucesso.
- A implementação garante maior cobertura de código e confiança na lógica dos endpoints.

---

## 📁 Estrutura dos Testes

```
src/
└── test/
    └── java/
        └── com/example/usuario/
            └── controller/
                └── UsuarioControllerTest.java
```

---

## ✅ Resultado

Todos os testes unitários foram implementados e aprovados com sucesso, assegurando que os métodos do controlador de usuários se comportam como esperado.
