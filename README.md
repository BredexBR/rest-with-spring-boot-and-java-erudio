# rest-with-spring-boot-and-java-erudio

# 🚀 Projeto: Desenvolva uma API REST do Zero e Implante na AWS

Este repositório contém o código desenvolvido durante o curso ["REST API's RESTFul do 0 à AWS c. Spring Boot 3 Java e Docker"](https://www.udemy.com/course/restful-apis-do-0-a-nuvem-com-springboot-e-docker/?kw=spring+aws&src=sac) da Udemy.<br>

O curso aborda a criação de uma API REST do zero, passando por:
<br>✔️ Conceitos fundamentais de REST e HTTP.
<br>✔️ Práticas avançadas com Spring Boot 3.
<br>✔️ Integração com banco de dados e segurança.
<br>✔️ Deploy na AWS utilizando Docker e outras tecnologias modernas.

## 📑 Índice

- [🚀 Tecnologias e Ferramentas Utilizadas](#🚀-tecnologias-e-ferramentas-utilizadas)
  - [🔹 Back-end](#🔹-back-end)
  - [🔹 Desenvolvimento e Testes](#🔹-desenvolvimento-e-testes)
  - [🔹 Segurança e Autenticação](#🔹-segurança-e-autenticação)
  - [🔹 Front-end e Orquestração](#🔹-front-end-e-orquestração)
  - [🔹 Controle de Versão](#🔹-controle-de-versão)
- [📂 Estrutura do Projeto](#📂-estrutura-do-projeto)
  - [📌 First Steps in Java with Spring Boot](#📌-05_firststepsinjavawithspringboot)
  - [📌 API HTTP Requests](#📌-07_apihttprequests)
  - [📌 Add Migrations](#📌-11_addmigrations)
  - [📌 Content Negotiation](#📌-13_contentnegotiation)
- [🏛️ Arquitetura do Projeto](#🏛️-arquitetura-do-projeto)
  - [🔹 Controller](#🔹-controller)
  - [🔹 Service](#🔹-service)
  - [🔹 Repository](#🔹-repository)
  - [🔹 Model](#-🔹model)
- [📝 Pré-requisitos](#📝-pré-requisitos)

## 🚀 Tecnologias e Ferramentas Utilizadas

### 🔹 Back-end:
- 🟢 Spring Boot 3
- ☕ Java 21
- 🌐 Arquitetura REST/RESTful
- 📂 Migrations com Flyway
- 🛢️ Integração com banco de dados MySQL
### 🔹 Desenvolvimento e Testes:
- 🧪 Testes unitários e de integração com:
  - ✅ JUnit 5
  - ✅ Mockito
  - ✅ REST Assured
  - ✅ Testcontainers
- 🔄 Versionamento de APIs
- 🔗 HATEOAS
- 📜 Swagger Open API
### 🔹 Segurança e Autenticação:
- 🔐 JWT (JSON Web Token) com Spring Security
- 🔹 Ferramentas e Integrações:
- 📬 Postman
- 📤 Upload e download de arquivos
- 🐳 Dockerização da Aplicação
- ☁️ Implantação na Amazon AWS
- 🔄 Integração Contínua na AWS com GitHub Actions
- 🧠 Integração com ChatGPT
### 🔹 Front-end e Orquestração:
- ⚛️ React JS
- ☸️ Kubernetes (K8s)
### 🔹 Controle de Versão:
- 🔀 Git e GitHub

## 📂 Estrutura do Projeto
### 📌 [05_FirstStepsInJavaWithSpringBoot](https://github.com/BredexBR/rest-with-spring-boot-and-java-erudio/tree/main/05_FirstStepsInJavaWithSpringBoot/rest-with-spring-boot-and-java-erudio)
#### 🔹 **Funcionalidades**:
- **Operações matemáticas:** Soma, subtração, multiplicação, divisão e raiz quadrada.
- **Requisições HTTP:** Get, Post, Put e Delete para manipulação de dados.
<br>

![Aula 5 e 6](imgs-readme/5.png)
<br>

#### 🌐 **O que é Rest?**
**REST (Representational State Transfer)** é um estilo de arquitetura para comunicação entre sistemas distribuídos, baseado em padrões da web. Ele define um conjunto de restrições, como a utilização do protocolo HTTP, operações sem estado (stateless) e a manipulação de recursos através de identificadores únicos (URIs). REST permite a interação entre clientes e servidores de forma simples, escalável e independente da tecnologia utilizada. 🚀

### 📌 [07_ApiHttpRequests](https://github.com/BredexBR/rest-with-spring-boot-and-java-erudio/tree/main/07_ApiHttpRequests/rest-with-spring-boot-and-java-erudio7)
#### 🔹 **Funcionalidades**:
- 📌 **Gerenciamento de Pessoas:** Adição e manipulação de atributos de pessoas na API.
- 🗄️ **Integração com Banco de Dados:** Conectando e armazenando dados de forma persistente.
- 🎯 **Padrão de Projeto VO (Value Object):** Implementação de boas práticas para estruturação dos dados.
- 🔄 **Versionamento de API:** Suporte a múltiplas versões para manter compatibilidade e evolução do sistema.
<br>

![Aula 7 até 10](imgs-readme/7.png)
<br>

#### 📦 **O que é VO?**
É um padrão de projeto em que um objeto é definido apenas pelos seus valores e não possui identidade própria. Ou seja, dois VOs com os mesmos valores são considerados iguais. Eles são imutáveis, garantindo consistência e evitando efeitos colaterais em aplicações.

### 📌 [11_AddMigrations](https://github.com/BredexBR/rest-with-spring-boot-and-java-erudio/tree/main/11_AddMigrations/rest-with-spring-boot-and-java-erudio11)
#### 🔹 **Funcionalidades**:
- 🔄 **Migrations com Flyway:** Gerenciamento de versão do banco de dados de forma automatizada.
- 🛠️ **Custom JSON Serialization:** Personalização da serialização JSON para definir a ordem e nomenclatura dos atributos retornados pela API.

#### 🔄 **O que são Migrations?**
São um processo de versionamento e controle das mudanças no banco de dados, permitindo que você gerencie a criação, alteração e remoção de tabelas, colunas e outros objetos de forma incremental. Elas garantem que a estrutura do banco de dados esteja sempre atualizada e consistente entre diferentes ambientes, como desenvolvimento, teste e produção. As migrations geralmente são automatizadas e podem ser aplicadas ou revertidas com comandos simples, facilitando a evolução do banco de dados ao longo do tempo. 🚀

<br>

![Aula 11 e 12](imgs-readme/11.png)
<br>

### 📌 [13_ContentNegotiation](https://github.com/BredexBR/rest-with-spring-boot-and-java-erudio/tree/main/13_ContentNegotiation/rest-with-spring-boot-and-java-erudio13)
#### 🔹 **Funcionalidades**:
- 🌍 **Content Negotiation:** Permite que a API retorne conteúdo em múltiplos formatos (JSON, XML, YAML, etc.).
- 🔗 **HATEOAS (Hypermedia as the Engine of Application State):** Adiciona links nas respostas da API para facilitar a navegação entre recursos.

<br>

![Aula 13 e 14](imgs-readme/13.png)

<br>

- 🧪 **Testes Unitários**
  - Utilização do Mockito e JUnit 5 para testar as funções:
    - 📌 **Create**
    - 📌 **Update**
    - 📌 **FindAll**
    - 📌 **FindById**
<br>

![Aula 13 e 14b](imgs-readme/13b.png)
<br>

- 📖 **Documentação com Swagger**
  - Adicionando suporte ao Swagger para facilitar a documentação e testes da API para os endpoints:
    - **Books**
    - **Person**
    - **Authentication**
  
<br>

![Aula 13 e 14c](imgs-readme/13c.png)
<br>

- 🔐 **Autenticação e Segurança**
  - 🏗️ Infraestrutura de testes utilizando Testcontainers e Rest Assured.
  - 🔒 **Segurança na API RESTful:**
    - **JWT (JSON Web Token):** Utilizado para autenticação sem armazenar estado no servidor.
    - **Spring Security:** Gerencia segurança e controle de acesso nas requisições.

#### 🌐 **O que é RESTful:**
É uma abordagem para criar APIs seguindo os princípios da arquitetura REST As operações em um recurso são feitas através de verbos HTTP (GET, POST, PUT, DELETE), e a comunicação é sem estado, ou seja, cada requisição contém todas as informações necessárias para ser processada, sem depender de interações anteriores. 🚀

#### 🌐 **o que é a "Glória do REST"**
Se refere à sua simplicidade e elegância. Ao seguir as diretrizes do REST, você cria APIs que são intuitivas, escaláveis e de fácil manutenção. A "glória" está no fato de que REST facilita a comunicação entre sistemas de maneira eficiente, transparente e alinhada com os padrões da web, o que o torna amplamente adotado para serviços web modernos. 🚀

## 🏛️ Arquitetura do Projeto
O projeto adota uma arquitetura em camadas, seguindo os padrões e boas práticas do Spring Framework, com o objetivo de garantir a separação de responsabilidades, escalabilidade e facilidade de manutenção. As principais camadas da arquitetura são:

### 🔹 Controller
A camada de Controller é responsável por gerenciar as requisições HTTP. Ela mapeia as rotas da API ou páginas da aplicação e interage com a camada de Service para processar as solicitações. O Controller não contém lógica de negócio, apenas gerencia as interações entre a interface do usuário (ou clientes da API) e o sistema.

### 🔹 Service
A camada de Service contém a lógica de negócio do sistema. Aqui, são definidos os processos que operam sobre os dados e são chamados pelos Controllers. Essa camada é responsável por encapsular regras de negócio e orquestrar os fluxos da aplicação.

### 🔹 Repository
A camada de Repository é responsável por acessar o banco de dados ou outras fontes de dados persistentes. Ela utiliza Spring Data JPA ou outras tecnologias de persistência para executar operações CRUD (Create, Read, Update, Delete) sobre as entidades da aplicação.

### 🔹 Model
A camada de Model representa as entidades ou objetos de dados utilizados na aplicação. Esses modelos podem ser diretamente mapeados para o banco de dados (caso de entidades JPA) ou utilizados para representar objetos de negócio que serão manipulados nas camadas superiores.

## 📝 Pré-requisitos
1. **Java 21**: Certifique-se de que o Java 21 está instalado na sua máquina.
2. **Docker**: Necessário para a execução de containers. Versão 27.4.0.
3. **MySQL**: Configuração do banco de dados. Versão 8.0.40.
4. **Postman**: Para testar a API.
5. **Java Spring Tool**: Framework na versão 3.3.7.
6. **Mvn**: Gerenciar as dependências e automatizar as builds. Versão 3.3.9.
