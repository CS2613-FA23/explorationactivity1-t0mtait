[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/oB7VDeFN)
# ExplorationActivity1


**Which package/library does the sample program demonstrate?**
<br> Express.js

**How does someone run your program?** <br>
You can run my program as a webapp or just test the API functionality via postman
##### setup (webapp)

- pull the code from this repo
- cd into the src folder in the terminal
- start the express server via the "node server" command in the terminal (make sure you're cd'd in correctly)
- start a local server for index.html page viewing (vscode has a live server available as an extension)
- open the html page and encrypt/decrypt away!

##### setup (postman)

- pull the code from this repo
- cd into the src folder in the terminal
- start the express server via the "node server" command in the terminal (make sure you're cd'd in correctly)

###### Encrypting
- set the postman method to POST
- set the postman URL to http://localhost:3000/encrypt
- set the body to raw json format
- input the following in the json body: "text": "string" (replace string with whatever you want to encrypt)
- click send!

###### Decrypting
- set the postman method to POST
- set the postman URL to http://localhost:3000/decrypt
- set the body to raw json format
- input the following in the json body: "text": "string" (replace string with encrypted text)
- click send!

**What purpose does your program serve?** <br>
My program is a basic encryptor app, it is used to make private data unreadable to other users.

**What would be some sample input/output?** <br>
input:<br> test <br> [encrypt] <br>
output: <br> 601c361797b8d48be44a13bd1e25115199c43d0cfe574ee88e63e5af37872ee42bb1dbdd358ab2bdbfe71b0c1724bb837acfbe17b6c26eb566872390159a3c3d1eadef8e2788a7105ecc3241785b2229de2a5a246ff4c1e0ba00786860eafb3be6a84f84 <br><br>
input: 601c361797b8d48be44a13bd1e25115199c43d0cfe574ee88e63e5af37872ee42bb1dbdd358ab2bdbfe71b0c1724bb837acfbe17b6c26eb566872390159a3c3d1eadef8e2788a7105ecc3241785b2229de2a5a246ff4c1e0ba00786860eafb3be6a84f84 <br> [decrypt] <br>
output: test
