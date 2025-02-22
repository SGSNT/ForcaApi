# Jogo da Forca - Backend

Este repositório contém a implementação do backend do **Jogo da forca** utilizando **Java** e **Spring Boot**. O objetivo deste projeto é fornecer a lógica de jogo, interações com o banco de dados e a API para que o frontend possa interagir com o backend.

O projeto foi iniciado com as estruturas básicas de diretórios e arquivos. A seguir, estão os passos realizados até o momento:

## 1. Configurações iniciais

- **Criação das pastas principais** para organizar a estrutura do projeto:
   - **`Service`**: Contém as regras de négocios do jogo.
   - **`Controller`**: Contém os controladores REST para expor os endpoints da API.
   - **`Entity`**: Contém as entidades do jogo (como `Word`,etc).
   - **`Repository`**: Contém as interfaces de acesso ao banco de dados(JPA Repositories).

## 2. Configurações do banco de dados
- As configurações de conexão com o banco de dados foram adicionadas no arquivo **`application.properties`** para permitir a conexão com o banco de dados.

   # Configurações do Banco de dados:

        spring.application.name=ForcaApi
        spring.datasource.url=jdbc:mysql://localhost:3306/forca
        spring.datasource.username=root
        spring.datasource.password=root
        spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
        spring.jpa.hibernate.ddl-auto=update
        spring.jpa.show-sql=true

    As depêndencias essenciais foram adicionadas no arquivo **`pom.xml`**.
 
