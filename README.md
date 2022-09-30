# tactical-tiger-blitz

REST API starter app using NodeJS, ExpressJS, TypeScript.


# Getting Started
Install `npm i`  
Start Server `npm run dev`

## How this project was built  
Install TypeScript `npm install -g typescript`  
Initialize NodeJS `npm init`  
Install dependencies `npm install typescript ts-node express @types/express morgan @types/morgan axios @types/axios nodemon`  
- TypeScript: A TypeScript compiler with static set type definitions.  
- Ts-node: Allows us to run and configure Typescript execution environments.  
- Express: NodeJS web application framework for setting and managing web-based server.  
- @types/express: Type definitions for Express.  
- Morgan: A NodeJS HTTP request logger middleware for NodeJS.  
- @types/morgan: Type definitions for Morgan.  
- Axios: A NodeJS promise-based HTTP client library for NodeJS, for sending HTTP requests to query and consume resources from APIs.  
- @types/Axios: Type definitions for Axios.  
- Nodemon: A server utility library for monitoring changes of the code on a text editor. It automatically restarts the server whenever code changes are detected.  
Initialize TypeScript `tsc --init`  
Update package.json  
`"main": "src/server.ts",  
"scripts": {  
    "dev": "nodemon src/server.ts",  
    "build": "rm -rf build/ && prettier --write source/ && tsc"  
}`
