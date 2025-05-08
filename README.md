# Checkpoint 2 - Microservice and Web Engineering (Spring Boot API)

Projeto desenvolvido como parte do **Checkpoint 2** da disciplina de Microservice and Web Engineering. Esta aplicação continua a proposta do Checkpoint 1, expandindo o controle de registros de uma clínica estética, agora com mais funcionalidades e organização das entidades.

## 🎯 Objetivo

Fornecer uma API REST mais robusta e estruturada para o controle de profissionais e pacientes de uma clínica estética, com rotas de autenticação, relacionamento entre entidades, documentação completa e boas práticas de projeto utilizando Spring Boot.

---

## 🚀 Tecnologias Utilizadas

- Java 17  
- Spring Boot  
- Spring Web  
- Spring Data JPA  
- H2 Database  
- Lombok  
- Swagger (Springdoc OpenAPI)

---

## 📦 Estrutura do Projeto

A aplicação está organizada nos seguintes pacotes:

- `model`: Contém as entidades `Paciente` e `Profissional`.
- `service`: Lógica de negócio para ambas as entidades.
- `controller`: Camada responsável por expor os endpoints da API REST.
- `dto`: Objetos de Transferência de Dados para facilitar o mapeamento entre requisições/respostas e entidades.
- `repository`: Interfaces responsáveis pela comunicação com o banco de dados.
- `config`: Configurações da API e do Swagger.

---

## ✅ Funcionalidades Implementadas

### 🔹 Paciente

- `GET /pacientes`: Retorna todos os pacientes.
- `GET /pacientes/{id}`: Retorna um paciente específico.
- `POST /pacientes`: Cadastra um novo paciente.
- `PUT /pacientes/{id}`: Atualiza dados de um paciente existente.
- `DELETE /pacientes/{id}`: Remove um paciente.

### 🔹 Profissional

- `GET /profissionais`: Lista todos os profissionais cadastrados.
- `GET /profissionais/{id}`: Retorna um profissional pelo ID.
- `POST /profissionais`: Cadastra um novo profissional.
- `PUT /profissionais/{id}`: Atualiza dados de um profissional.
- `DELETE /profissionais/{id}`: Remove um profissional do sistema.

---

## 🧪 Banco de Dados

A aplicação utiliza o banco de dados **H2 em memória**, facilitando os testes durante o desenvolvimento.  
Acesse a interface H2 via:  
📍 `http://localhost:8080/h2-console`

---

## 📑 Documentação da API

A API possui documentação interativa disponível via Swagger:

📍 `http://localhost:8080/swagger-ui/index.html`

---

## 🔧 Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/RaphaelBatizati/Checkpoint2Microservers.git
