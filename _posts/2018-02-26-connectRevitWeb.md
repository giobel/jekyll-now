---
title: Connect Revit to the Web
layout: post
---

A cookbook made from [The 3D Web Coder](http://the3dwebcoder.typepad.com/)website by Jeremy Tammik

Ingredients:

- [Brackets](http://brackets.io/) open source text editor. Live preview on browser. 

- Pipenv


- Node.js open source, cross-platform JavaScript runtime environment. Use it to build a web server.
Tutorials and Workshops: 
```python
 $ npm install -g learnyounode
 $ npm install -g introtowebgl
```



Recipes

nodejs Hello World
```python
  var http = require('http');

  http.createServer(function (req, res) {
    res.writeHead(200, {'Content-Type': 'text/plain'});
    res.end('Hello World\n');
  }).listen(1337, '127.0.0.1');

  console.log('Server running at http://127.0.0.1:1337/');
```
Run the server
```python
  % node example.js
  Server running at http://127.0.0.1:1337/
```