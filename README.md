# GetURL - A URL Shortener Frontend

GetURL is a **URL Shortener Frontend** developed using **React JS** and interact with backend built using **Expressjs** , which is used to shorten the **Long URL** into **Shorten URL**. **[URL-Shortener-Microservice]  provides **REST API** endpoints to interact with.

## Run Locally

1. Clone the project
```
 git clone 
```
2. Open **[VS Code](https://spring.io/tools)** or any other IDE of your choice open the **GetURL-URL-Shortener-Frontend** folder.

3. In terminal chnage directory to the **GetURL-URL-Shortener-Frontend** folder.
 -   For Windows
    ```
      cd GetURL-URL-Shortener-Frontend
    ```
4. If you don't have Node on your machine then download [Node](https://nodejs.org/en/download/) and [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm).

5. Now run npm to install the required dependencies.
```
  npm install
```
6. Now start the react app by this command
```
  npm start
```
## ⚠ Caution
- This project might run on your machine but not working properly because don't have proper connection to the backend.
- Use or Build any backend of your choice and expose your API URL in **.env** file on your project root directory.
  ```
    REACT_APP_API_URL=https://api.yourdomain.com
  ```
- If you are familiar with **Java** and **Spring Boot** you can clone my project URL-Shortener-Microservice and run it as a backend.

😊 Happy Coding 🎉

## API Reference of Backend for your use.

#### Get all urls 

```
  GET /urls
```
```http
  http://localhost:5000/urls
```

#### Get a url details

```
  GET /${id}/details
```

```http
  http://localhost:5000/random_id/details
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of Shorten Url to fetch details|

#### Post a url

```
  POST /urls
```

```http
  http://localhost:5000/urls
```

| Request body | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `originalUrl`      | `string` | **Required**. originalUrl of Long URL to create shorten link.|

#### Get request to shorten link which redirects to its original URL

```
  GET /${id}
```

```http
  http://localhost:5000/random_id
```

## Dependencies Used

- **[Animate.css](https://animate.style/)**
  Animate.css is a library of ready-to-use, cross-browser animations for use in your web projects. Great for emphasis, home pages, sliders, and attention-       guiding hints.
  ```
    npm install animate.css --save
  ```
 - **[AXIOS](https://www.npmjs.com/package/axios)**
    Promise based HTTP client for the browser and node.js.
    ```
      npm install axios
    ```
- **[Bootstrap](https://getbootstrap.com/)**
  Powerful, extensible, and feature-packed frontend toolkit. Build and customize with Sass, utilize prebuilt grid system and components, and bring projects to life with powerful JavaScript plugins.
  ```
    npm i bootstrap@5.3.0-alpha1
  ```
- **[Bootstrap Icons](https://icons.getbootstrap.com/)**
  Free, high quality, open source icon library with over 1,800 icons. Include them anyway you like—SVGs, SVG sprite, or web fonts. Use them with or without Bootstrap in any project.
  ```
    npm i bootstrap-icons
  ```
- **[React](https://reactjs.org/docs/getting-started.html)**
 A JavaScript library for building user interfaces.

- **[React Copy to Clipboard](https://www.npmjs.com/package/react-copy-to-clipboard)**
  Copy to clipboard React component
  ```
    npm install --save react-copy-to-clipboard
  ```
- **[ReactDOM](https://reactjs.org/docs/react-dom.html)**
 The react-dom package provides DOM-specific methods that can be used at the top level of your app and as an escape hatch to get outside the React model if you need to.
 
- **[React Router DOM](https://www.npmjs.com/package/react-router-dom)**
  The react-router-dom package contains bindings for using React Router in web applications.
  ```
    npm i react-router-dom
  ```
- **[React Scripts](https://www.npmjs.com/package/react-scripts)**
  This package includes scripts and configuration used by Create React App
  ```
    npm i react-scripts
  ```
- **[TypewriterJS v2](https://www.npmjs.com/package/typewriter-effect)**
  A simple yet powerful native javascript plugin for a cool typewriter effect.
  ```
    npm i typewriter-effect
  ```
- **[validator.js](https://www.npmjs.com/package/validator)**
  A library of string validators and sanitizers.
  ```
    npm i validator
  ```
## Author

<p>
  <b align="right"> Vishesh Jain </b>
</p> 


## Show your support

Give a ⭐️ if this project helped you!


