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

♻️ O galaxy é um app responsável por criar aplicações para cliente da Goldie It. Utilizando a base de código da empresa, este app faz comunicação através de envio de dados em json contendo "tags" responsáveis por fazer o cadastro e montar componentes de uma tela.

Os components são formados por um json, que através de escolhas do usuário através do app, cria pastas e arquivos contendo códigos PHP com HTML e css, tornando o desenvolvimento da aplicação apenas por cliques através de um app para Android e Ios.

##### english

Galaxy is an app responsible for creating applications for Goldie It customers. Using the company's code base, this app communicates by sending data in json containing "tags" responsible for making trips and assembling components on a screen.

The components are formed by a json, which through user choices through the app, creates folders and files containing PHP codes with HTML and css, making the application development just by clicks through an app for Android and Ios

---

## Features

Exemplo de construção de um component dentro do Galaxy:

- [x] Qual será a missão?
      nome da requisicao (request)
- [x] Qual nave iremos?
      tipo de requisicao, shared,modal,page (req_option)
- [x] Onde iremos?
      componente ou plugin? e o metodo ..... se for componente não colocar o "plugin" se for plugin, colocar o "plugin" e o "sendToPlugin" (json)
- [x] O que será enviado?
      se for shared (mandar via o shared) se for plugin (sendToPlugin)
- [x] Cheguei ao destino, preciso esperar algo?
      existe algum shared dentro do local de destino?
- [x] O que será retornado?
      Html,data,Form,Todos juntos
- [x] EU devo deixar em algum lugar?
      insert, caso a mesma rota tenha que se inserir (insert_into)
- [x] Faço algo mais com isso?
      response_control, pode parar a req, limpar parametros, limpar formulario,etc... (json)
- [x] Cheguei, mais alguma coisa?
      proxima sequencia

##### english

Example of building a component within the Galaxy:

- [x] What will be the mission?
      request name (request)
- [x] Which ship will we go to?
      request type, shared, modal, page (req_option)
- [x] Where will we go?
      component or plugin? and the method ..... if it is a component do not put the "plugin" if it is a plugin, put the "plugin" and "sendToPlugin" (json)
- [x] What will be sent?
      if it is shared (send via shared) if it is plugin (sendToPlugin)
- [x] I arrived at the destination, do I need to wait for something?
      is there any shared within the destination location?
- [x] What will be returned?
      Html, data, Form, All together
- [x] Should I leave it somewhere?
      insert, if the same route has to be inserted (insert_into)
- [x] Do I do anything else with this?
      response_control, you can stop the req, clear parameters, clear forms, etc ... (json)
- [x] I arrived, anything else? next sequence

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
    "@fortawesome/fontawesome-svg-core": "^1.2.32",
    "@fortawesome/free-solid-svg-icons": "^5.15.1",
    "@fortawesome/react-fontawesome": "^0.1.13",
    "@fortawesome/react-native-fontawesome": "^0.2.6",
    "@react-native-community/async-storage": "^1.12.1",
    "@react-native-community/masked-view": "^0.1.10",
    "@react-native-community/slider": "^3.0.3",
    "@react-native-community/voice": "^1.1.9",
    "@react-native-picker/picker": "^1.9.4",
    "@react-navigation/native": "^5.8.10",
    "@react-navigation/stack": "^5.12.8",
    "axios": "^0.21.0",
    "formik": "^2.2.5",
    "react": "16.13.1",
    "react-native": "0.63.3",
    "react-native-color-picker": "^0.6.0",
    "react-native-draggable-flatlist": "^2.5.1",
    "react-native-gesture-handler": "^1.9.0",
    "react-native-iphone-x-helper": "^1.3.1",
    "react-native-modal": "^11.5.6",
    "react-native-picker-select": "^8.0.4",
    "react-native-progress-steps": "^1.3.4",
    "react-native-reanimated": "^1.13.2",
    "react-native-restart": "^0.0.20",
    "react-native-safe-area-context": "^3.1.9",
    "react-native-screens": "^2.15.0",
    "react-native-shake": "^3.5.0",
    "react-native-slider-color-picker": "^2.2.1",
    "react-native-svg": "^12.1.0",
    "react-native-webview": "^11.0.2",
    "react-query": "^3.5.1",
    "styled-components": "^5.2.1",
    "tinycolor2": "^1.4.2"
  },
```
