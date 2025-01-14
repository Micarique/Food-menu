<h1>Cardápio Digital - Backend</h1>

<p align="center">
  <a href="#pre-requisites">Pré-requisitos</a> •
  <a href="#how-to-use">Instalando o projeto</a> •
  <a href="#related">Frontend</a> •
  <a href="#license">Licença</a>
</p>

A implementação do backend foi desenvolvida com base no conteúdo do vídeo [Construindo aplicação Fullstack do ZERO](https://youtu.be/lUVureR5GqI?si=d-fHBagSO6bjX58G). aplicação foi desenvolvida usando **Java Spring, Lombok, Flyway e banco de dados PostgreSQL.** e simula um servidor que armazena informações de um cardápio digital no banco de dados.

**OBJETIVO:** Explorar a criação de um servidor com **Java Spring e Spring MVC**, a manipulação e persistência de dados com o **Spring Data JPA**, a geração de boilerplates com o **Lombok**, a conexão com banco de dados Postgres através do **Postgres Driver** e o gerenciamento e versionamento de mudanças no esquema do banco de dados através do **Flyway**.

Esta parte do projeto é responsável pela criação do servidor e manipulação do banco de dados do cardápio.

<h2 id="pre-requisites">💻 Requisitos</h2> 

Para rodar esse projeto você precisa ter o Java instalado na sua máquina.

<h2 id="how-to-use"> 🚀 Instalando o projeto</h2>

Primeiro você deve clonar o repositório,

```bash
# Clone o repositório
$ git clone https://github.com/fernandakipper/crud-java-back

# Acesse-o
$ cd crud-java-back
```

Agora, dentro do IntelliJ, vamos instalar as depedências com o Maven

<img width="300px" src="./.github/instalar-deps.png">

E por fim, entre no arquivo da classe `CardapioApllication` para executar o projeto

<img width="300px" src="./.github/executar.png">

<h2 id="related">🫂 Integração com Frontend</h2>

Para realizar a integração com o Frontend, você pode clonar o projeto e rodar localmente, ou desenvolver você mesmo seguindo o tutorial no Youtube.

👉 [Desenvolvendo o Frontend desse Cardápio Digital com React e Typescript](https://www.youtube.com/watch?v=WHruc3_2z68)

👉 [Link do repositório original](https://github.com/Fernanda-Kipper/frontend-cardapio-digital)


<h2 id="license">📝 Licença</h2>

Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para obter mais informações.


