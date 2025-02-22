# Implementação das configurações iniciais
 
 ## Descrição:

 Este Pull Request contém as configurações iniciais para o projeto do **backend do jogo**. As seguintes tarefas foram realizadas:
 
- **Criação das pastas principais para organizar a estrutura do projeto**:

  - `Service`: Adicionada a pasta para armazenar as regras de negócios do jogo.
  - `Controller`: Adicionada a pasta para armazenar os controladores REST.
  - `Entity`: Adicionada a pasta para as entidades do jogo.
  - `Repository`: Adicionada a pasta para armazenar as interfaces de acesso ao banco de dados.
  

- Adição de dependências no `pom.xml`:

  - Dependências essenciais para o funcionamento do **Spring Boot** e integração com banco de dados **MySql** foram adicionadas.
 
 
- Configuração do banco de dados no `application.properties`:


  - Configuração para conectar o projeto ao banco de dados MySql com as credenciais e configurações apropriadas.


 ## Como Testar:

      1. Clone o repositório.
      2. Execute o servidor Spring Boot
      3. Verifique se as pastas: Service,Controller,Repositoy e Entity estão criadas e estruturadas corretamente.
      4. Confira o arquivo pom.xml para garantir que as dependências estão corretamente incluídas.
      5. Verifique o arquivo application.properties para validar se as configurações do banco de dados estão corretas.


 ## Tipo de mudança:

    - [✔] Nova Funcionalidade
    - [] Correção de bug
    - [] Alteração no banco de dados
    - [] Melhoria na performance
    - [] Outros (Explique)

 ## Checklist:

    - [✔] A estrutura do projeto foi organizada e as pastas necessárias foram criadas
    - [✔] As dependências essenciais foram adicionadas corretamente no arquivo pom.xml
    - [✔] A configuração do banco de dados foi corretamente adicionadas no arquivo application.properties
    - [✔] O código segue as diretrizes de estilo do projeto
