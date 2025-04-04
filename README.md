🚀 Demo - Spring Boot com MongoDB
Projeto de demonstração utilizando Spring Boot 3.4.4, MongoDB e Java 21. Esta aplicação serve como base para projetos que exigem uma arquitetura simples, moderna e escalável com persistência de dados NoSQL.

📦 Tecnologias Utilizadas
✅ Spring Boot 3.4.4

✅ Java 21

✅ MongoDB

✅ Maven

🧰 Funcionalidades
Integração com MongoDB utilizando Spring Data

Estrutura modular e pronta para produção

Scripts Maven para build e execução

Suporte a testes automatizados (se configurado)

🚀 Como Executar o Projeto
Clone o repositório:
git clone https://github.com/seu-usuario/seu-repositorio.git
cd demo
Configure o MongoDB:

Certifique-se de que o MongoDB esteja em execução localmente (localhost:27017) ou configure a URI no application.properties/application.yml.
Compile e execute a aplicação:
./mvnw spring-boot:run
Acesse a aplicação:

Por padrão: http://localhost:8080/

🧪 Testes
Execute os testes com:
./mvnw test
🗂 Estrutura do Projeto
demo/
├── src/
│   ├── main/
│   │   ├── java/          # Código-fonte Java
│   │   └── resources/     # Arquivos de configuração
│   └── test/              # Testes unitários
├── pom.xml                # Configuração Maven
