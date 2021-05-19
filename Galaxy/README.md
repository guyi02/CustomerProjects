<h1 align='center'>
Galaxy
</h1>

<h4 align="center"> 
	 Status: Developing
</h4>

<p align="center">
 <a href="#about">About</a> •
 <a href="#features">Features</a> •
  <a href="#tech-stack">My Tasks</a> •
 <a href="#layout">Layout</a> • 
 <a href="#tech-stack">Tech Dependencies</a> •

</p>

## About

♻️ O galaxy é um app responsável por criar aplicações para cliente da Goldie It. Utilizando a base de código da empresa, este app faz comunicação através de envio de dados em json contento "tags" responsáveis por fazer viagens e montar componentes de uma tela.

Os components são formados por um json, que através de escolhas do usuário através do app, cria pastas e arquivos contendo códigos PHP com HTML e css, tornando o desenvimento de aplicação apenas por cliques através de um app para Android e Ios

##### english

Galaxy is an app responsible for creating applications for Goldie It customers. Using the company's code base, this app communicates by sending data in json containing "tags" responsible for making trips and assembling components on a screen.

The components are formed by a json, which through user choices through the app, creates folders and files containing PHP codes with HTML and css, making the application development just by clicks through an app for Android and Ios

---

## Features

Exemplo de construção de um component dentro do Galaxy:

1 - Qual será a missão?
nome da requisicao (request)
2 - Qual nave iremos?
tipo de requisicao, shared,modal,page (req_option)
3 - Onde iremos?
componente ou plugin? e o metodo ..... se for componente não colocar o "plugin" se for plugin, colocar o "plugin" e o "sendToPlugin" (json)
4 - O que será enviado?
se for shared (mandar via o shared) se for plugin (sendToPlugin)  
5 - Cheguei ao destino, preciso esperar algo?
existe algum shared dentro do local de destino?  
6 - O que será retornado?
Html,data,Form,Todos juntos  
7 - EU devo deixar em algum lugar?
insert, caso a mesma rota tenha que se inserir (insert_into)
8 - Faço algo mais com isso?
response_control, pode parar a req, limpar parametros, limpar formulario,etc... (json)
9 - Cheguei, mais alguma coisa?
proxima sequencia

##### english

Example of building a component within the Galaxy:

1 - What will be the mission?
request name (request)
2 - Which ship will we go to?
request type, shared, modal, page (req_option)
3 - Where will we go?
component or plugin? and the method ..... if it is a component do not put the "plugin" if it is a plugin, put the "plugin" and "sendToPlugin" (json)
4 - What will be sent?
if it is shared (send via shared) if it is plugin (sendToPlugin)
5 - I arrived at the destination, do I need to wait for something?
is there any shared within the destination location?
6 - What will be returned?
Html, data, Form, All together
7 - Should I leave it somewhere?
insert, if the same route has to be inserted (insert_into)
8 - Do I do anything else with this?
response_control, you can stop the req, clear parameters, clear forms, etc ... (json)
9 - I arrived, anything else? next sequence

---

## My Tasks

Este projeto foi uma oportunidade de experimentas novas ferramentas, pude utilizar a biblioteca 'React-query' que é reponsável por fazer requições e já manter um cache como estado, permitindo o re-uso mais a frente. TypeScript foi utilizado a todo momento, paara que cada component contenha uma boa leitura e entendimento.

##### english

This project was an opportunity to try new tools, I was able to use the library 'React-query' which is responsible for making requests and already maintaining a cache as a state, allowing re-use later on. TypeScript was used at all times, so that each component contains a good reading and understanding.

---

## Layout

![](gif-galaxy.gif)

## Tech Dependencies

Lista de dependências utilizada para construção deste projeto / List of dependencies used to build this project:

```javascript
    "dependencies": {
        "@connectedcars/react-native-slide-charts": "^1.0.5",
        "@react-native-community/async-storage": "^1.7.1",
        "@react-native-community/geolocation": "^2.0.2",
        "@react-native-community/google-signin": "^4.0.3",
        "@react-native-community/masked-view": "^0.1.6",
        "axios": "^0.19.1",
        "babel-plugin-transform-remove-console": "^6.9.4",
        "d3-shape": "^2.0.0",
        "i18n-js": "^3.5.1",
        "lodash": "^4.17.19",
        "lodash.memoize": "^4.1.2",
        "moment": "^2.29.1",
        "react": "^16.9.0",
        "react-native": "0.61.5",
        "react-native-calendars": "^1.261.0",
        "react-native-gesture-handler": "^1.5.3",
        "react-native-image-picker": "^3.1.4",
        "react-native-iphone-x-helper": "^1.2.1",
        "react-native-linear-gradient": "^2.5.6",
        "react-native-localize": "^1.3.2",
        "react-native-masked-text": "^1.13.0",
        "react-native-modal": "^11.5.6",
        "react-native-onesignal": "^4.0.4",
        "react-native-paper": "^3.4.1",
        "react-native-permissions": "^3.0.3",
        "react-native-picker-select": "^7.0.0",
        "react-native-progress-circle": "^2.1.0",
        "react-native-reanimated": "^1.7.0",
        "react-native-responsive-screen": "^1.3.1",
        "react-native-restart": "0.0.17",
        "react-native-safe-area-context": "^0.6.2",
        "react-native-screens": "^2.0.0-alpha.25",
        "react-native-share": "^5.1.4",
        "react-native-shimmer-placeholder": "^1.0.35",
        "react-native-snap-carousel": "^3.8.4",
        "react-native-star-rating": "^1.1.0",
        "react-native-step-indicator": "^0.0.11",
        "react-native-svg": "^11.1.0",
        "react-native-svg-charts": "^5.4.0",
        "react-native-swiper-flatlist": "^2.0.3",
        "react-native-switch-selector": "^2.0.4",
        "react-native-vector-icons": "^7.0.0",
        "react-native-view-shot": "^3.1.2",
        "react-navigation": "^4.0.10",
        "react-navigation-stack": "^2.0.15",
        "react-navigation-tabs": "^2.7.0",
        "reactotron-react-native": "^4.0.2",
        "rn-fetch-blob": "^0.12.0",
        "styled-components": "^5.0.0",
        "throttle-debounce": "^2.1.0",
        "use-state-with-callback": "^1.0.18"
    }
```
