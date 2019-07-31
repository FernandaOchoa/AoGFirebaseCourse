# Curso Aprende a crear un Chatbot con Actions on Google, DialogFlow y Firebase Functions/Firestore

![Google Assistant](https://xapp-wpengine.netdna-ssl.com/wp-content/uploads/2018/07/google-assistant-devices-01-1024x526.png)

## Presentación

Hola que tal amigos de CódigoFacilito mi nombre es Fernanda Ochoa y te doy la Bienvenida a este nuevo curso llamado Agentes Inteligentes con DialogFlow, AoG y Firebase.

Actions en Google es una plataforma para desarrolladores que te permite crear software para ampliar la funcionalidad de Google Assistant, el asistente personal virtual de Google, en más de 500 millones de dispositivos, incluidos altavoces inteligentes, teléfonos, automóviles, televisores, auriculares y más.

### Requerimientos para este curso
Las siguientes herramientas deben estar en su entorno:

* Un navegador web, como Chrome.
* Una cuenta en DialogFlow
* Una cuenta en Firebase
* Un editor de texto (en mi caso será atom)
* Conocimientos básicos de Programación
* Deseable aunque no indispensable conocimiento básico de JS, si no sabes absolutamente nada te recomiendo nuestro Curso Profesional de Javascript impartido por [Uriel](https://codigofacilito.com/cursos/javascript-profesional). 

### Agenda

![Agenda](https://firebasestorage.googleapis.com/v0/b/hackcf-1a937.appspot.com/o/Schedule.png?alt=media&token=f1fca0d6-07e0-4af0-bc5c-04f30cde72c8)
### Temario

* Presentacion del curso
* JS para AoG 
* Creación de un proyecto (TacoBot) 
* Slot-Filling 
* Fulfillment 
* Custom Entities
* Implement a Webhook
* Empezando con Firebase
* Firebase Functions
* Webhooks para Cody Hacks 
* Firebase DB [Firestore]
* Show RSVPs
* Follow Up Intent
* Deployment
* Que aprendimos, Despedida

#### Version 2 API DialogFlow
Para usar la versión 2 del API de dialogflow es necesario cambiar el path de la variable *params* de la siguiente manera.  

    let params = request.body.queryResult.parameters;


#### Demo TacoBot   
![Demo TacoBot](https://firebasestorage.googleapis.com/v0/b/hackcf-1a937.appspot.com/o/tacobot.gif?alt=media&token=28a185e9-6411-4c74-a02c-e607db9efe01) 

### Demo Cody Hack en Assistant
![](https://firebasestorage.googleapis.com/v0/b/hackcf-1a937.appspot.com/o/HackFull.gif?alt=media&token=1462a00b-dcbe-4d7b-844d-662c6dfadc05)


### Demo Cody Hack en Web
![Demo](https://firebasestorage.googleapis.com/v0/b/hackcf-1a937.appspot.com/o/DemoWeb.png?alt=media&token=de1fbac3-4a4c-4739-b014-4a6c5c57c13b)

### Firebase
![Firebase](https://firebasestorage.googleapis.com/v0/b/hackcf-1a937.appspot.com/o/back.gif?alt=media&token=e707b4b7-3815-4984-a6a8-e8db63903415)

### Recursos
* **Privacy Policy [Guide](https://developers.google.com/actions/policies/privacy-policy-guide)**

* **Privacy Policy [Generator](https://app-privacy-policy-generator.firebaseapp.com/#)**

* **Privacy Policy [Sample](https://sites.google.com/view/rsvphack/home)**

## License

This repository it's under Apache License.
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,  
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

