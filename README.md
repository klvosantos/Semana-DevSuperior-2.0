# DS Deliver
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/klvosantos/dsdeliver-sds2/blob/main/LICENSE) 

# Sobre o projeto

https://sds2-marcelo.netlify.app

DS Deliver é uma aplicação full stack web e mobile construída durante a 2ª edição da **Semana DevSuperior** (#sds2), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação web possibilita a realização de pedidos de refeições, assim que a refeição é escolhida é inserido uma localização para onde o pedido devera ser entregue. Já no app mobile é identificado os pedidos pelo entregador, sendo assim possível de ser realizado entrega e confirmação de entrega.

## Layout mobile
![Mobile 1](https://github.com/klvosantos/assets/blob/main/sds2/mobile-all.jpg)

## Layout web
![Web 1](https://github.com/klvosantos/assets/blob/main/sds2/web.jpg)

## Modelo conceitual
![Modelo Conceitual](https://github.com/klvosantos/assets/blob/main/sds2/modelo-conceitual.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native
- Leaflet + MapBox
- Expo
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/klvosantos/dsdeliver-sds2

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/klvosantos/dsdeliver-sds2

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
yarn start
```

# Autor

Marcelo Santos

https://www.linkedin.com/in/marcelosantosms
