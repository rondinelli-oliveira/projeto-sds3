# DSVendas 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/rondinelli-oliveira/projeto-sds3/blob/master/LICENSE) 

# Sobre o projeto

https://rondinelli-dsvendas.netlify.app

DSVendas é uma aplicação full stack web construída durante a 3ª edição da **Semana DevSuperior** (#sds3), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em um sistema que simula as vendas de uma equipe, onde os dados são armazeanados em uma base de dados e depois são listados na interface web, que também apresenta um dashboard com gráficos baseados nestes dados.

## Layout web
![Web 1](https://github.com/rondinelli-oliveira/projeto-sds3/blob/master/assets/home.png)

![Web 2](https://github.com/rondinelli-oliveira/projeto-sds3/blob/master/assets/dash.png)

## Modelo conceitual
![Modelo Conceitual](https://github.com/rondinelli-oliveira/projeto-sds3/blob/master/assets/derdsvendas.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- Apex Charts
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/rondinelli-oliveira/projeto-sds3

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/rondinelli-oliveira/projeto-sds3

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
yarn start
```

# Autor

Rondinelli de Oliveira Silva

https://www.linkedin.com/in/rondinelli-oliveira-3937ab93/
