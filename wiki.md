**Which package/library did you select?**
I chose the ExpressJS Package

**What is the package/library?**
Express is a webapp framework used to create API's

**What purpose does it serve?**
Express was created to make APIs and web applications with ease,
The reason behind creating an express framework for node js is:
<ul>
<li>Speed</li>
<li>Scalability</li>
<li>Economical</li>
<li>Simplicity</li>
<li>Asynchronous</li>
<a href = "https://www.simplilearn.com/tutorials/nodejs-tutorial/what-is-express-js#:~:text=BootcampExplore%20Program-,What%20Is%20Express%20JS%3F,helps%20manage%20servers%20and%20routes.">[Reference #1]</a>
</ul>


**How do you use it?**

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
<li>Routing</li>
<li>Middleware</li>
<li>HTTP Methods</li>
<li>Static file serving</li>
<li>Error handling</li>
<li>Security features</li>
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
