# Desafio Empregados Auth - TDD resolvido

Foram implementadas as funcionalidades necessárias para que os testes do projeto passassem.

## Relacionamento
Este é um sistema de funcionários e departamentos com uma relação N-1 entre eles, e o relacioanmento
de Users e Roles.
![Diagrama de classes](.github/relacionamento.png "Department - Employee - Auth")


## Testes de Integração
Os testes de integração foram feitos com o banco de dados em memória H2, e para isso foi utilizado o
módulo `spring-boot-starter-data-jpa` e `spring-boot-starter-test` para a configuração do banco de dados
e para a configuração do teste, respectivamente.
![Diagrama de classes](.github/testes.png "Testes - Realizados")

#### Links
<img title="Postman Icon" src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40">[ Postman Collection](.github/DesafioEmpregadosAuth.postman_collection.json)