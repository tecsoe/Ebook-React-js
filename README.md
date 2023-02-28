# Beneficiosi
[Tubeneficiosi.com](http://tubeneficiosi.com/) es una plataforma tipo marketplace, que cuenta con aplicación web y móvil desarrollada principalmente con [React.js](https://es.reactjs.org/) Donde clientes y vendedores realizan transacciones de compra y venta de productos y eventos.

![](https://i.imgur.com/ZPj3gPp.png)

## Videos Tutoriales

* [Introducción a la aplicación Web](https://www.youtube.com/watch?v=TzYGaBXAwQc)

## Caracteristicas del Proyecto

* Desarrollo de aplicaciones responsivas.
* Desarrollo de aplicaciones administrativas (Tiendas y Administrador del markerplace).
* RESTFUL APIs.
* Procesador de pago.
* Motor de búsqueda.
* Despliegue en servidor.

## Caracteristicas del Marketplace Beneficiosi

* Plataforma moderna para economía bajo demanda y mercados digitales.
* ¡Todo reactivo, en tiempo real y ultrarrápido!
* Personalización del sitio web de comercio electrónico de compras para que los clientes realicen compras de alimentos, bienes o servicios a pedido en el navegador.
* Sitio web de administración utilizado para administrar todas las funciones y configuraciones de la plataforma en una interfaz Web.
* Catálogos de productos con múltiples imágenes de productos, variantes de productos, facetas y búsqueda de texto completo.
* Pasarela y procesamiento de pagos (Pasarela de pago admitida actualmente - Mercado libre).
* Integraciones de proveedores de envío de terceros.

## Tecnologias

* [React.js](https://es.reactjs.org/) Actualmente una de las más empleadas para el desarrollo web y mantenida por Facebook.
* [React-Native ](https://reactnative.dev/) React-Native Utilizasa para de desarrollar aplicaciones para Android.
* [Node.js](https://github.com/Tecsoess/Node/wiki) Node.js De gran demanda actual, debido a que es considerada tecnología líder en desarrollo para servidores.
* [Tailwindcss](https://tailwindcss.com/) Tailwindcss Framework de CSS que brinda los componentes basicos para crear diseños personalizados.
* [Material IU](https://mui.com/) Material IU Permite importar y usar diferentes componentes para crear una interfaz de usuario en nuestras aplicaciones React.
* [NestJS](https://github.com/Tecsoess/NEST.JS) NestJS Este framework para el desarrollo de aplicaciones en el lado del servidor, proporciona una arquitectura que permite un desarrollo más facil de mantener.
* [TypeScript]([https://github.com/Tecsoess/Typescript](https://github.com/Tecsoess/Typescript)) TypeScript Lenguaje superconjunto de Javascript que esencialmente añade tipos estáticos y objetos basados en clases.
* [MySQL](https://www.mysql.com/) MySQL Sistema de gestion de base de datos relacionales que emplea un modelo cliente-servidor.

## Detalles del Desarrollo

### Marketplace

* 100% responsiva, se adapta a los tamaños de pantallas más comunes.
* En comunicación con el backend se realizan envíos de correos electrónicos para casos como registro de usuario, olvido de contraseña entre otras opciones.
* Websocket para notificaciones y chat en tiempo real.

### Panel de administración de las Tiendas

* 100% responsiva, se adapta a los tamaños de pantallas más comunes.
* Control de parámetros y opciones relacionadas con las tiendas del Marketplace.
* En comunicación con el backend se realizan envíos de correos electrónicos para casos como registro de usuario, olvido de contraseña entre otras opciones.
* Websocket para notificaciones y chat en tiempo real.

### Backend

* Procesos programados para ejecuciones automáticas que requiera el cliente: envío de notificaciones, correos electrónicos entre otros.
* Websockets para comunicaciones en tiempo real.
* Procesador de pago y motor de búsqueda.

## Perfiles: Cliente, Tienda y Administrador.

* ## Cliente
    Frontend principal para el marketplace Beneficio Si
    
    * Link : https://github.com/tecsoe/beneficiosi-clients-front-Components

## Instalación

```
git clone https://github.com/tecsoe/beneficiosi-clients-front-Components.git
cd beneficiosi-clients-front-Components
npm install
cp .env-example .env
```

## Configurar variables de entorno en el archivo .env

```
npm run start
```

* ## Administrador
Frontend de administración para el marketplace [Beneficio Si](http://tubeneficiosi.com/)

 * Link : https://github.com/Tecsoess/beneficiosi-admins-front


## Instalación

```
git clone https://github.com/Tecsoess/beneficiosi-admins-front.git
cd beneficiosi-admins-front
npm install
cp .env-example .env
```

###Configurar variables de entrono en el archivo .env
```
npm run start
```

### API de Beneficiosi

API de conexión para el marketplace Beneficio Si
    * Link: https://github.com/Tecsoess/beneficiosi-api
    
## Instalación

```
git clone https://github.com/ICKillerGH/beneficiosi-api.git
cd beneficiosi-api
npm install
cp .env-example .env
```

## Configurar variables de entorno en el archivo.env
```
npm run start:dev
```

### APP movil de Beneficiosi

Aplicaion móvil creada en [React-Native ](https://reactnative.dev/) para el marketplace [Beneficio Si](http://tubeneficiosi.com/)

![](https://i.imgur.com/SuzDBkd.png)

## Requisitos

* [NodeJs](https://nodejs.org/es/download/)
* [Android Studio]()

## Instalación e Inicialización

1. Clonar el repositorio.
2. Cambiar a la rama develop.
3. Instalar las dependencias con node.
4. Iniciar el emulador android o conectar el dispositivo android a la pc por usb.
5. Iniciar la app 5.1 Iniciar el bundle 5.2 Compilar la app.

```
git clone https://github.com/JeyverVegas/BeneficioSiApp.git
git checkout develop
npm i
react-native
react-native run-android
```

### Seguridad

En una configuración de producción, todas las comunicaciones del lado del cliente al lado del servidor (backend, API) deben cifrarse mediante HTTPS/WSS/SSL (API REST, extremo de GraphQL, Socket.io WebSockets, etc.).

Si descubre algún problema relacionado con la seguridad, divulgue la información de manera responsable enviando un correo electrónico a atencionalcliente@beneficiosi.com

### Indice de Ebooks

* [React.js](https://github.com/Tecsoess/Ebook-React-js/wiki)
    * [React.js Essentials]( )
    * [React by example]( )
    * [React Cookbook]( )
    * [Full stack react]( )
    * [Introduction to react]( )
    * [Learning react]( )
    * [Getting with react]( )
    * [Design patterns and best practices]( )
    * [Learning ext js]( )
    * [React]( )
    * [Full stack development with graph and react]( )
    
* [React Native](https://github.com/Tecsoess/Ebook-React-js/wiki)
    * [Getting started with react native]( )
    * [Practical react native]( )
    * [React Native cookbook]( )
    * [30 Days of react]( )
    * [Mastering react]( )
    * [Fullstack react]( )
    * [Getting started with react( )
    * [Mastering react natives]( )
    * [React and react native]( )
    * [React native blueprints]( )
    * [React native tutorials point]( )
    * [Android apps]( )










