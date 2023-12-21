### A real-time code editor made using React.js, Node.js, Express.js, Websocet.io

Its deployed on railway, check [here](https://github.com/4vinn/cypher-code-editor).

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
> From :
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