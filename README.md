# XACM Editor

El reto mas grande que se tiene en este backend es que va a ser diferente a los demás, ya que este tiene que tener funcionalidades tanto del WebSocket server como de acciones HTTP para los modelos que se definan.
Entonces, en un principio se tiene que conseguir lo siguiente tomando en cuenta que se va a trabajar con YJS, hay que tener en cuenta los aspectos importantes:

- YJS trabaja con una estructura que la llaman Doc(), esta estructura se crea desde el frontend y se relaciona con una conexión al servidor de WebSocket
- YJS tiene que tener un servidor de websocket totalemente funcional para que pueda procesar los documentos comparitdos escritos.
- En los demos el servidor se hace de manera primitiva con el el modulo _http_ de node. Sin embargo, de aqui se desprende un reto que se va a describir mas adelante.
- Los demos que nos interesan estan en los siguientes enlaces:
  - https://github.com/yjs/yjs/blob/master/README.md#Getting-Started
  - https://github.com/yjs/y-monaco?tab=readme-ov-file
  - https://github.com/yjs/yjs-demos/blob/main/demo-server/demo-server.js

En un principio, gran parte del trabajo va por parte del front-end, sin embargo, es importante tener un servidor WebSocket funcional para probar las funcionalidades.
