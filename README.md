# Dependencias
```
npm i express mongoose cors dotenv zod

npm i -D typescript ts-node-dev @types/node @types/express @types/cors

npx tsc --init (para tsconfig)
```
### -D -> Significa agregarlo como devDependecies en el package.json

<br/>

## CompilerOptions (tsconfig)

```
"compilerOptions": {
    "target": "es2020",
    "module": "commonjs",
    "rootDir": "./src",
    "outDir": "./dist",
    "esModuleInterop": true,
    "strict": true,
    "skipLibCheck": true
  }
```
<br/>

## Scripts
```
 "scripts": {
    "dev": "ts-node-dev --respawn --transpile-only src/index.ts",
    "build": "tsc",
    "start": "node dist/index.js"
  },
```
