# dsdeliver-sds2

https://tavares-sds2.netlify.app/

DS Delivery é uma aplicação full stack web e mobile construída durante a 2ª edição da **Semana DevSuperior** (#sds2), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em um sistema de pedido e entrega de restaurante. Os dados da solicitação do pedido são coletados via web e posteriormente os pedidos são entregues e confirmados no app mobile.

## Layout Mobile

![mobile1](https://user-images.githubusercontent.com/73531971/111190898-4d18ed80-8596-11eb-8237-cec6e1d0ffc0.jpeg) 

![mobile2](https://user-images.githubusercontent.com/73531971/111190912-5013de00-8596-11eb-84b2-1e65a92645f1.jpeg) 

![mobile3](https://user-images.githubusercontent.com/73531971/111190917-530ece80-8596-11eb-9585-0b40d2016346.jpeg)

## Layout Web

![1](https://user-images.githubusercontent.com/73531971/111189101-82244080-8594-11eb-8507-a5ce9d910632.PNG)

![2](https://user-images.githubusercontent.com/73531971/111189117-87818b00-8594-11eb-9e28-09775017261e.PNG)

![3](https://user-images.githubusercontent.com/73531971/111189128-8a7c7b80-8594-11eb-88c9-41dd68269641.PNG)

## Modelo conceitual

![sds2_modelo-conceitual](https://user-images.githubusercontent.com/73531971/111189342-be57a100-8594-11eb-901b-748169968cb1.png)

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
- Apex Charts
- Expo

## API
- Mapbox

## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/GabrielTavares96/dsdeliver-sds2.git

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/GabrielTavares96/dsdeliver-sds2.git

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
npm install

# executar o projeto
npm start
```

## Front end mobile
Pré-requisitos: npm / expo

```bash
# clonar repositório
git clone https://github.com/GabrielTavares96/dsdeliver-sds2.git

# entrar na pasta do projeto front end web
cd front-mobile

# instalar dependências
expo install @react-navigation/stack @react-native-community/masked-view react-native-screens react-native-gesture-handler @react-navigation/native expo-app-loading @expo-google-fonts/open-sans expo-font

# executar o projeto
npm start
```

# Autor
[Gabriel Tavares](https://www.linkedin.com/in/gabriel-pereira-tavares-8a2618b6/ "Perfil Linkedin Gabriel Tavares")
