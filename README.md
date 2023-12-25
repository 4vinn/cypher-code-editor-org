### A real-time code editor made using React, Node, Express, socet.io

Changed the repo structure for deployment on Railway. **Know more [here](https://github.com/4vinn/cypher-code-editor).**

>For that, I restructured my repo into a monorepo:
```
.
├── .gitignore
├── README
├── frontend/
│   ├── public
│   ├── src
|   |   ├── components
│   |   ├── pages
|   |   └── actions.js
│   ├── package.json
│   └── package-lock.json
└── backend/
    ├── server.js
    ├── actions.js
    ├── package.json
    └── package-lock.json
```
> Original structure :
```
.
|
├── public
├── src
|   ├── components
│   ├── pages
|   └── actions.js
|   
├── .gitignore
├── README    
├── server.js    
├── package.json
└── package-lock.json    
```


Another code editor:
```
https://akormous.medium.com/building-a-shared-code-editor-using-node-js-websocket-and-crdt-e84e870136a1
```
