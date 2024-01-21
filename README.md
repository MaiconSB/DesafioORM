# Desafio: Modelo de Domínio e ORM

## Descrição do Projeto

Projeto Spring Boot com Java e banco de dados H2, implementando o modelo conceitual para gerenciar informações dos participantes das atividades de um evento acadêmico.

### Tecnologias Utilizadas

- Spring Boot
- Java
- Banco de dados H2
- Maven

### Configuração do Ambiente de Desenvolvimento

Certifique-se de ter o Maven instalado e configurado em sua máquina. Clone o repositório e execute:

```bash
mvn clean install
```
###  Executando o Projeto
Para executar o projeto, utilize o seguinte comando:
```bash
mvn spring-boot:run
```
O projeto estará acessível em http://localhost:8080.

### Banco de Dados
O H2 Console pode ser acessado em http://localhost:8080/h2-console. Certifique-se de utilizar as configurações corretas (driver, URL, usuário e senha) para acessar o banco de dados.

Seeding da Base de Dados
Ao iniciar o projeto, a base de dados será populada automaticamente com os dados do seeding.

### Modelo Conceitual
O modelo conceitual inclui as seguintes entidades:

* Atividade
* Bloco
* Categoria
* Participante
* Atividade_Participante (relacionamento entre Atividade e Participante)
* Instância dos Dados para Seeding
* Os dados do seeding estão disponíveis no arquivo data.sql.

### Contribuição
Sinta-se à vontade para contribuir para o projeto. Para isso, siga o processo padrão de fork, branch, commit e pull request.
