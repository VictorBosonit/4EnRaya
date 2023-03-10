# 4 en raya con reactive y websockets

Hemos desarrollado una aplicaci贸n basada en Spring Reactive, Websockets y Angular con la cual se puede jugar multijugador, chatear y todos los datos de la partida 
son guardados en MongoDB.

## Comenzando 馃殌

Antes de poder lanzar la aplicaci贸n vamos a necesitar tener una serie de programas instalados para la correcta ejecuci贸n. Ponemos una peque帽a lista de las dependencias
de esta.


### Pre-requisitos 馃搵

_Software necesario para la ejecuci贸n correcta de la aplicaci贸n_

#### Backend

- Java 17
- MongoDB

#### Frontend

- Angular
  - SweetAlert2
  - Bootstrap
  - SocksJS
  - Stomp

### Instalaci贸n 馃敡

_Ponemos a continuaci贸n los comandos necesarios para poder iniciar la aplicaci贸n_

- Angular
  - Para comenzar instalaremos SweetAlert2 que es una extensi贸n para Angular
```
npm install --save sweetalert2
```
- SocketJS
  - Para instalar SocketJS
 ```
 npm i @types/socksjs-client--save-dev
 npm install sockjs-client
 ```
- Stomp
  - Para instalar STOMP (que usaremos para websockets)
 ```
 npm install @stomp/stompjs@5.2.0 --save
 ```
 - Hacemos un peque帽o update para tener todo actualizado
```
npm update
```
Para que funcione correctamente, hay que cambiar el application-properties del backend para que conecte adecuadamente con el mongoDB 
(en nuestro caso dentro de un contenedor de Docker)

## Autores 鉁掞笍

* **Andr茅s Cioppi Mettler**
* **Victor Rubio Ib谩帽ez**
* **Jose del R铆o Hermo**
* **Jose Alberto Corzo Mate**
