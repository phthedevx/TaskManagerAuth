# Controle de Tarefas com Autenticação (Java + Spring Boot)

Aplicação web para gerenciamento de tarefas com autenticação de usuários usando Spring Security.

## 🚀 Funcionalidades
- Cadastro e login de usuários
- CRUD de tarefas por usuário
- Autenticação e autorização com Spring Security
- API RESTful
- Banco de dados MySQL 
## 🛠️ Tecnologias
- Java 17+
- Spring Boot
- Spring Data JPA
- Spring Security
- Maven
- MySQL ou H2

## ▶️ Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/task-manager-auth.git
   cd task-manager-auth
   ```

2. Configure o banco de dados em `src/main/resources/application.properties`.

3. Execute:
   ```bash
   ./mvnw spring-boot:run
   ```

4. Acesse [http://localhost:8080](http://localhost:8080)

## 📁 Estrutura Sugerida
```
src/
  ├── controller/
  ├── model/
  ├── repository/
  ├── security/
  ├── service/
  └── TaskManagerApplication.java
```

## 📄 Licença
MIT
