# Testcontainers Demo Application

## Descrição
Esta aplicação é um exemplo de como usar o Testcontainers com Spring Boot para testar interações com um banco de dados PostgreSQL. Ela demonstra como configurar testes de integração que utilizam um container Docker para o banco de dados.

## Funcionalidades
- Listar todos os clientes
- Testes de integração com banco de dados PostgreSQL usando Testcontainers

## Pré-requisitos
- Java 11 ou superior
- Maven 3.6 ou superior
- Docker

## Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/andersonnogueiraalu/testcontainers-customer

2. Navegue até o diretório do projeto:
   ```bash
   cd seu-repositorio

## Como Executar

 - Para iniciar a aplicação, execute o seguinte comando:
   ```bash
   mvn spring-boot:run
   
 - A aplicação estará disponível em http://localhost:8080

## Executando os Testes

Para garantir que a aplicação está funcionando corretamente, você pode executar os testes de integração. Siga os passos abaixo:
  1. Certifique-se de que o Docker está em execução.
  2. Execute os testes :
      ```bash
     mvn test

Os testes verificarão se todas as funcionalidades da aplicação estão operando conforme o esperado, utilizando um container PostgreSQL para simular o ambiente de produção.

## Contribuição
Se você deseja contribuir com este projeto, por favor, siga as diretrizes de contribuição e envie um pull request.

