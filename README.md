# User Service

Sample application that exposes a Rest API through 8080 port

#### Pre-Requisites

* NodeJS Installed

#### Install

```npm install```<br>
Run to install all required Node modules.

#### Run the App

```node .```<br> 
Run to exeute the server and start listening at 8080 port.

#### REST API

#### Getting a polite Hello

```GET /user```<br>
```code
curl -il http://localhost:8080/user
```

#### Response

```code
HTTP/1.1 200 OK
X-Powered-By: Express
Content-Type: text/html; charset=utf-8
Content-Length: 25
ETag: W/"19-MG/TJs8cAIR0/m8/X6/tsxyFnzo"
Date: Sat, 16 Dec 2023 18:51:02 GMT
Connection: keep-alive
Keep-Alive: timeout=5

Hello World User Service!
```

#### Questions and Feedback?

Find me on the Linkedin as lazevedo-devops or feel free to contact me through mail lazevedo@darkscreen.io.