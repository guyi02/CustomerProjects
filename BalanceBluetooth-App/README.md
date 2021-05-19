<h1 align='center'>
Aplicativo de pesagem através de bluetooth / 
Weighing app via bluetooth
</h1>

<h4 align="center"> 
	 Status: Finished
</h4>

<p align="center">
 <a href="#about">About</a> •
 <a href="#features">Features</a> •
  <a href="#tech-stack">My Tasks</a> •
 <a href="#layout">Layout</a> • 
 <a href="#tech-stack">Tech Dependencies</a> •

</p>

## About

♻️ Este aplicativo tem a finalidade de pesar embalagens de ovos, que são armazenadas em caixas. As caixas são formadas por pilhas de embalagens que ao preencherem toda a caixa, somam um valor total para a mesma. A pesagem é feita através de uma balança de baixo porte conectada via Bluetooth, tornando a pesagem em etapas, até atingir o seu preenchimento.

##### english

This application is intended to weigh egg packages, which are stored in boxes. The boxes are made up of stacks of packaging that when filling the entire box add up to a total value for it. Weighing is done through a small balance connected via Bluetooth, making the weighing in stages, until it reaches its completion.

#### Imagem da balança utilizada no projeto / Image of the balance used in the project

![image info](https://i.imgur.com/Fhhtm7q.png)

---

## Features

- [x] Usuário pode se autenticar / user can authenticate
- [x] Usuário pode ver lista de notas de entrada de um novo produto / users can see list of notes of incoming products
  - confere se a nota recebida está de acordo com a pesagem / checks if the note received is in accordance with the weighing
  - usuário preenche campo com o peso da caixa recebida / user fills in field with the weight of the box received
  - após verificar, app envia dados para api e em seguida imprima uma etiqueta na impressora / after checking, app sends data to api and then print a label on the printer
- [x] Usuário pode ver lista de pedidos a serem pesados / user can see list of orders to be weighed
  - inicia produção de uma nova caixa de embalagens / starts production of a new packaging box
  - uma nova tela que contenha o peso que a caixa precisa atingir / a new screen contains the weight that the box needs to reach
  - usuário inicia pesagem de uma caixa / user starts weighing a box
  - a caixa é dividida em andares, cada peso é dividido por 3 andares, ao atingir um andar uma modal com um alerta abre fazendo um som de aviso / the box is divided into floors, each weight is divided by 3 floors, when reaching a floor a modal with an alert opens making a warning sound
  - usuário inicia pesagem de uma caixa / user starts weighing a box
  - ao preencher um andar da caixa, é retirado os produtos da balança conectada, o app salva o peso do andar em localStorage e o usuário inicia a pesagem já somando com o peso atingido do andar anterior / when filling a floor of the box, the products are removed from the balance connected, the app saves the weight of the floor in localStorage and the user starts weighing already adding to the weight reached from the previous floor

---

## My Tasks

No presente projeto pude desenvolver toda a interface através de códigos em React e a comunicação com as apis vindas do backend. Utilizando da biblioteca "react-native-bluetooth-serial-next" pude conectar o app via bluetooth a uma balança de pesagem , que a cada segundo envia o peso atual contido na mesma.

O cliente atualmente utiliza o aplicativo em um tablet dentro de seu depósito, portanto o layout em landscape (horizontal) precisaria estar de acordo com os wareframes desenvidos e aprovados pelo cliente.

Foi a primeira experiencia em trabalhar em um app que conecta-se a um periferico externo, trazendo assim novos desafios e aprendizados durante o desenvolvimento.

##### english

In this project i was able to develop the entire interface through React codes and communication with the backend apis. Using the library "react-native-bluetooth-serial-next" I was able to connect the app to bluetooth to a weighing balance, which sends the current weight in it every second.

The customer currently uses the application on a tablet within his warehouse, so the landscape (horizontal) layout would need to be in accordance with the wareframes developed and approved by the customer.

It was the first experience of working on an app that connects to an external periphery, bringing new challenges and learning during development.

---

## Layout

![](gif-hlplast-app.gif)

- Teste com balança conectado via Bluetooth / Test connected in Bluetooth

[![app - teste balança](https://i.imgur.com/WVLji1L.png)](https://youtu.be/taqgwDc-Qa8)

## Tech Dependencies

Lista de dependências utilizada para construção deste projeto / List of dependencies used to build this project:

```javascript
"dependencies": {
    "@fortawesome/fontawesome-svg-core": "^1.2.30",
    "@fortawesome/free-solid-svg-icons": "^5.14.0",
    "@fortawesome/react-native-fontawesome": "^0.2.5",
    "@react-native-community/async-storage": "^1.11.0",
    "@react-native-community/masked-view": "^0.1.10",
    "@react-navigation/drawer": "^5.9.0",
    "@react-navigation/native": "^5.7.2",
    "@react-navigation/stack": "^5.8.0",
    "@types/styled-components": "^5.1.2",
    "axios": "^0.20.0",
    "react": "16.13.1",
    "react-native": "0.63.0",
    "react-native-bluetooth-serial-next": "^1.2.3",
    "react-native-gesture-handler": "^1.7.0",
    "react-native-modal": "^11.5.6",
    "react-native-orientation-locker": "^1.2.0",
    "react-native-reanimated": "^1.10.1",
    "react-native-responsive-screen": "^1.4.1",
    "react-native-restart": "^0.0.17",
    "react-native-safe-area-context": "^3.1.1",
    "react-native-screens": "^2.9.0",
    "react-native-sound": "^0.11.0",
    "react-native-svg": "^12.1.0",
    "styled-components": "^5.1.1"
  }
```
