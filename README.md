<p align="center">
  <img alt="My Money" src=".github/banner.svg" width="400px"/>
</p>

<p align="center">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/rafaelfachinelli/mymoney?color=3498db&style=for-the-badge">
  <img alt="Last commit" src="https://img.shields.io/github/last-commit/rafaelfachinelli/mymoney?color=3498db&style=for-the-badge">
  <a href="https://rafaelfachinelli.com">
    <img alt="Developed by Rafael Fachinelli" src="https://img.shields.io/badge/Developer-Rafael_Fachinelli-3498db?style=for-the-badge">
  </a>
  <img alt="License" src="https://img.shields.io/badge/License-MIT-3498db?style=for-the-badge">
</p>

<p align="center">
  <a href="#information_source-about">About</a> •
  <a href="#memo-tasks">Tasks</a> •
  <a href="#arrow_forward-run">Run</a> •
  <a href="#hammer_and_wrench-technologies">Technologies</a> •
  <a href="#boy-author">Author</a> •
  <a href="#balance_scale-license">License</a>
</p>

---

## :information_source: About

💰 Personal finance app organized by billing cycles: each cycle (name, month and year) has its credits and debts, and a dashboard sums them up. The backend is a REST API with Node.js, Express and MongoDB (Mongoose with pagination, generated with node-restful); the frontend is a React admin panel with the AdminLTE template.

Built in 2021 to study a full JavaScript stack.

---

## :memo: Tasks

<div align="center">
<details>
<summary>Click to view</summary>

<details>
<summary>🗄️ Backend</summary>

|State|Task|
|:---:|:---|
|:heavy_check_mark:|Express server with CORS and query parsing|
|:heavy_check_mark:|MongoDB connection with Mongoose|
|:heavy_check_mark:|Billing cycle model with credits and debts|
|:heavy_check_mark:|REST service with node-restful and pagination|
|:heavy_check_mark:|Error handler|
|:heavy_check_mark:|Production run with PM2|

</details>

<details>
<summary>🌐 Frontend</summary>

|State|Task|
|:---:|:---|
|:heavy_check_mark:|AdminLTE template: header, sidebar, menu and footer|
|:heavy_check_mark:|Routes|
|:heavy_check_mark:|Dashboard|
|:heavy_check_mark:|Billing cycles page|

</details>

</details>
</div>

---

## :arrow_forward: Run

You need [Node.js](https://nodejs.org/) and MongoDB running on `localhost`.

### Backend

In the [`backend/`](backend/) folder:

```bash
# Install dependencies
yarn

# Start the API
yarn dev
```

> The API starts at <http://localhost:3003>.

### Frontend

In the [`frontend/`](frontend/) folder:

```bash
# Install dependencies
npm install

# Start the development server
npm run dev
```

---

## :hammer_and_wrench: Technologies

<div align="center">

|Backend|Frontend|
|:---:|:---:|
|[Node.js](https://nodejs.org/)|[React](https://react.dev/)|
|[Express](https://expressjs.com/)|[AdminLTE](https://adminlte.io/)|
|[MongoDB](https://www.mongodb.com/)|[Axios](https://axios-http.com/)|
|[Mongoose](https://mongoosejs.com/)|[Webpack](https://webpack.js.org/)|
|[node-restful](https://github.com/baugarten/node-restful)|[Babel](https://babeljs.io/)|
|[PM2](https://pm2.keymetrics.io/)||

</div>

---

## :boy: Author

<div align="center">

<a href="https://rafaelfachinelli.com">
  <img src="https://github.com/rafaelfachinelli.png" width="100px" alt="Rafael Fachinelli"/>
  <br/>
  <sub><b>Rafael Fachinelli</b></sub>
</a>

Tech Lead and software engineer. Get in touch!

[![Portfolio](https://img.shields.io/badge/-rafaelfachinelli.com-3498db?style=flat-square&logo=googlechrome&logoColor=white)](https://rafaelfachinelli.com)
[![LinkedIn](https://img.shields.io/badge/-Rafael_Fachinelli-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rafaelfachinelli/)
[![GitHub](https://img.shields.io/badge/-rafaelfachinelli-000?style=flat-square&logo=github&logoColor=white)](https://github.com/rafaelfachinelli)
[![E-mail](https://img.shields.io/badge/-rafael.l.a.fachinelli@gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:rafael.l.a.fachinelli@gmail.com)

</div>

---

## :balance_scale: License

This project is under the [MIT license](./LICENSE).
