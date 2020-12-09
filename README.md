### api de auth login + protected routes

## iniciar server con:
 `npm run dev`

 `npm start`



POST
http://localhost:3004/api/v1/user/register/
{
    "name": "",
    "email": "",
    "password": ""
}

POST
http://localhost:3004/api/v1/user/login/
{
    "email": "",
    "password": ""
}

GET
http://localhost:3004/api/v1/admin

Header: {"auth-token":"TOKEN"}


#### para activar el modo history en vue se instala

` npm i connect-history-api-fallback `

si tienes la carpeta public en la api inserta:

`//main route delete.. and insert to: `

` const history = require('connect-history-api-fallback')`
` app.use(history());`
` app.use(express.static(__dirname + "/public"));`

`//start server `