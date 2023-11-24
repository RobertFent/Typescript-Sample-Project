# Typescript Sample Project
This is a sample project for basic typescript projects consisting of a backend and maybe a frontend and so on.

### Contents
- configuration and setup for eslint
- prettier configuration for code formatting according to rules
- nodemon configuration for enabling hot reload and quick development due to running the backend with ts-node
- tsconfig configuration in root dir and backend dir so it can be extended for multiple backends or even frontend using typescript
- vscode configuration for suggestion extensions and enabling eslint with prettier

### How to run the project (from root folder)
Install all dependencies
```
npm i
```
Start backend where the backend gets compiled and run the compiled server by node.
```
npm run start:backend
```
Start backend by nodemon. The backend does not get compiled and the server is run by ts-node and hotreload is enabled.
```
npm run dev:backend
```