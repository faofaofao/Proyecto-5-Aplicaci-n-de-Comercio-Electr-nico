## Tecnologías incorporadas

- create-react-app (React.js)
- Tailwind CSS (Manejo de estilos)
- Express.js (Node)
- MongoDB

## Instalación

Para realizar la instalación de este proyecto, es necesario realizar `clone` o `fork` de este repositorio.

Posteriormente, abrir dos terminales. El primero será para tratar `create-react-app` y el otro para `express.js`.

`Terminal 1`
```shell
$ cd client
$ npm install
$ npm run start
```

`Terminal 2`
```shell
$ cd server
$ npm install
$ npm run dev
```


Una vez hecho esto en cada uno, deberás crear las variables de entorno en cada carpeta.

`./client/.env`

```
REACT_APP_BACKEND_URL="http://localhost:3005"
REACT_APP_MERCADO_PAGO_PUBLIC_KEY='TU-NÚMERO-DE-MERCADOPAGO-PARA-ACTIVAR-PAGOS'
```


`./server/.env`

```
PORT=3005
MONGODB_URI='mongodb://localhost:27017/proyecto-final-guitarras'
SECRET=PALABRASECRETADEBESCAMBIARLA
PROD_ACCESS_TOKEN='TU-NÚMERO-DE-MERCADOPAGO-PARA-ACTIVAR-PAGOS'
```

