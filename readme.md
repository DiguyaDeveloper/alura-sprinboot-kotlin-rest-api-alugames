# AluGames API

[![Kotlin](https://img.shields.io/badge/Kotlin-2.2.10-blueviolet?logo=kotlin)](https://kotlinlang.org/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-N%2FA-lightgrey?logo=springboot)](https://spring.io/projects/spring-boot)
[![Maven](https://img.shields.io/badge/Maven-Build-blue?logo=apachemaven)](https://maven.apache.org/)
[![Alura](https://img.shields.io/badge/Alura-Curso-blue?logo=alura)](https://cursos.alura.com.br/course/kotlin-desenvolvendo-primeira-aplicacao)

## Sobre o Projeto

Este projeto é um estudo prático de desenvolvimento de uma API REST utilizando **Kotlin** e **Maven**. Ele segue o conteúdo do curso [Kotlin: desenvolvendo sua primeira aplicação](https://cursos.alura.com.br/course/kotlin-desenvolvendo-primeira-aplicacao) da Alura.

O objetivo é consolidar conhecimentos em Kotlin aplicados ao desenvolvimento backend, explorando conceitos como:

- Estruturação de projetos Kotlin com Maven
- Criação de endpoints RESTful
- Manipulação de dados e entidades
- Boas práticas de desenvolvimento

## Como executar

1. **Pré-requisitos**:
   - [JDK 21+](https://adoptium.net/)
   - [Maven](https://maven.apache.org/)
   - [IntelliJ IDEA](https://www.jetbrains.com/idea/) (recomendado)

2. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/springboot-kotlin-rest-api-alugames.git
   cd springboot-kotlin-rest-api-alugames/AluGames
   ```

3. **Compile e execute a aplicação**:
   ```bash
   mvn clean package
   mvn exec:java
   ```
   > O `mainClass` está configurado como `MainKt` no POM. Ajuste se necessário.

4. **Acesse a API**:
   - Acesse: [http://localhost:8080](http://localhost:8080)

## Estrutura do Projeto

```
AluGames/
├── src/
│   └── main/
│       ├── kotlin/
│       └── resources/
├── pom.xml
└── readme.md
```

## Referências

- [Documentação oficial do Kotlin](https://kotlinlang.org/docs/home.html)
- [Maven](https://maven.apache.org/guides/)
- [Curso na Alura](https://cursos.alura.com.br/course/kotlin-desenvolvendo-primeira-aplicacao)

---

> Projeto desenvolvido para fins de estudo, acompanhando o curso da Alura.
> Projeto desenvolvido para fins de estudo, acompanhando o curso da Alura.
