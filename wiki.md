**Which package/library did you select?**
I chose the ExpressJS Package

**What is the package/library?**
Express is a webapp framework used to create API's

**What purpose does it serve?**
Express was created to make APIs and web applications with ease,
Some of the reasons behind choosing express are:
<ul>
<li>Speed</li>
<li>Scalability</li>
<li>Simplicity</li>
<a href = "https://www.simplilearn.com/tutorials/nodejs-tutorial/what-is-express-js#:~:text=BootcampExplore%20Program-,What%20Is%20Express%20JS%3F,helps%20manage%20servers%20and%20routes.">[Reference #1]</a>
</ul>


**How do you use it?**<br>
Install Express using the following command

```npm install express```

Embedded below is essentially the simplest Express app you can create.
```
const express = require('express')
const app = express()
const port = 3000

app.get('/', (req, res) => {
  res.send('Hello World!')
})

app.listen(port, () => {
  console.log(`Example app listening on port ${port}`)
})
```
``` const express = require('express')```
import express for use in the app.js file

```const app = express()```
create an express server instance named app

```const port = 3000```
assign port 3000 to be the port used by your server

```
app.get('/', (req, res) => {
  res.send('Hello World!')
})
```
Define the root request to send a 'Hello World!' response

```app.listen(port, () => {
  console.log(`Example app listening on port ${port}`)
}
```
Tell the express server to begin listening for requests on port 3000

Run the app with the following command:

```
node app.js
```

This app starts a server and listens on port 3000 for connections. The app responds with “Hello World!” for requests to the root URL (/). For every other path, it will respond with a 404 Not Found.
<a href = "https://expressjs.com/en/starter/hello-world.html">[Reference #2]</a>

**What are the functionalities of the package/library?**

<ol>
<li> Routing <br>
Routing refers to how an application’s endpoints (URIs) respond to client requests. <a href = "https://expressjs.com/en/guide/routing.html">[Reference #3]</a></li>

<li>Middleware<br>
Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle.
<a href = "https://expressjs.com/en/guide/using-middleware.html">[Reference #4]</a></li>

<li>HTTP Methods<br>
Express supports methods that correspond to all HTTP request methods: get, post, and so on.<a href = "https://expressjs.com/en/guide/routing.html">[Reference #5]</a></li>

<li>Static file serving<br>
Express offers users the ability to serve static files such as images, CSS files, and JavaScript files</li>

<li>Error handling<br>
Express comes with a default error handler so you don’t need to write your own to get started.<a href = "https://expressjs.com/en/guide/error-handling.html">[Reference #6]</a></li>
 
<li>Database integration</li>
<li>Rest API Development</li>
<li>High performance</li>
</ol>
**When was it created?**
Node was initially released, for Linux only, in 2009. The npm package manager was released in 2010, and native Windows support was added in 2012.
<a href = "https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction">[Reference #3]</a>

**Why did you select this package/library?**

**How did learning the package/library influence your learning of the language?**

**How was your overall experience with the package/library?**
