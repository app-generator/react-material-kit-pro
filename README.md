# [React Material Kit PRO](https://appseed.us/product/material-kit-pro/full-stack/)

Start your Development with an Innovative Admin Template for **Material-UI** and **React**. `Material Kit 2 React PRO` is built with over 100 frontend individual elements, like buttons, inputs, navbars, alerts or cards, giving you the freedom of choosing and combining. The product comes with a simple JWT authentication flow: login/register/logout. 

- 👉 [React Material Kit PRO](https://appseed.us/product/material-kit-pro/full-stack/) - `product page`
- 👉 [React Material Kit PRO](https://react-material-kit-pro.appseed-srv1.com/) - `LIVE Demo`

<br />

> Features:

- ✅ Innovative **Material Kit PRO** - Crafted by [Creative-Tim](https://bit.ly/3fKQZaL)
- ✅ React, Redux, Redux-persist
- ✅ Full-stack ready using **[Node JS API Server](https://appseed.us/boilerplate-code/nodejs-starter/)** (open-source project)
  - Features: Typescript / SQLite / TypeORM / Joy (validation) / Passport library - `passport-jwt` strategy.

<br />

![React Material Kit PRO - Premium Fullstack starter crafted by Creative-Tim and AppSeed.](https://user-images.githubusercontent.com/51070104/205701266-e721435d-22fc-48f2-9462-11f7fb050143.png)

<br />

## Tests

> `Compatibility matrix` using Ubuntu `18.04 LTS` as reference.

| NodeJS | NPM | YARN | 
| --- | --- | --- |  
| `v14.0.0` | ✅ | ❌ |
| `v15.0.0` | ✅ | ❌ | 
| `v16.15.0` | ✅ | ✅ | 

<br />

## ✨ How to use it

To use the product Node JS (>= 14.x) is required and GIT to clone/download the project from the public repository.

> 👉 **Step #1** - Download the product source code

```bash
$ unzip react-material-kit-pro.zip
$ cd react-material-kit-pro
```

<br >

> 👉 **Step #2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

> 👉 **Step 3** - Edit the `.env` using the template `.env.sample`. 

```env

REACT_APP_BACKEND_SERVER='http://localhost:5000/api/'

```

<br />

> 👉 **Step #4** - Start in development mode

```bash
$ npm run start 
// OR
$ yarn start
```

<br />

## ✨ Configure the backend server

The product comes with a usable JWT Authentication flow that provides only the basic requests: login/logout/register. 

> 👉 **API Server URL** - `src/config/constant.js` 

```javascript
const config = {
    ...
    API_SERVER: 'http://localhost:5000/api/'  // <-- The magic line
};
```

<br />

> 👉 **API Server Descriptor** - POSTMAN Collection

The API Server signature is provided by the [Unified API Definition](https://docs.appseed.us/boilerplate-code/api-unified-definition)

- [API POSTMAN Collection](https://github.com/app-generator/api-server-unified/blob/main/api.postman_collection.json) - can be used to mock (simulate) the backend server or code a new one in your preferred framework. 

<br />

## ✨ Node JS API Server

The product is also open-source and is already configured to work with Berry Dashboard Template - product features:

- Typescript / Node js / Express server
- JWT authentication (`passport-jwt` strategy)
- Persistence: SQLite 

> Links

- [Node JS API](https://github.com/app-generator/api-server-nodejs) - source code
- [Node JS API](https://appseed.us/boilerplate-code/nodejs-starter) - product page

<br />

![Node JS API - Open-source API server built on top of Express Nodejs Framework.](https://user-images.githubusercontent.com/51070104/124934824-c210a700-e00d-11eb-9d01-e05bd8bfb608.png)

<br />

### Compile the API Server

> 👉 **Step #1** - Clone the project

```bash
$ git clone https://github.com/app-generator/api-server-nodejs.git
$ cd api-server-nodejs
```

> 👉 **Step #2** - Install dependencies via NPM or Yarn

```bash
$ npm i
// OR
$ yarn
```

> 👉 **Step #3** - Run the SQLite migration via TypeORM

```
$ yarn typeorm migration:run
```

> 👉 **Step #4** - Start the API server (development mode)

```bash
$ npm dev
// OR
$ yarn dev
```

The API server will start using the `PORT` specified in `.env` file (default 5000).

<br /> 

---
[React Material Kit PRO](https://appseed.us/product/material-kit-pro/full-stack/) - Provided by **[AppSeed](https://appseed.us/app-generator)**.
