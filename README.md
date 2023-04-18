## Setup

```
npm init --yes

# Install TypeScript and its NodeJS wrapper
npm i typescript ts-node @types/node --save-dev

# Also initialize a TS configuration file that uses modern JavaScript
npx tsc --init --target es2020

npm install @feathersjs/feathers --save

npm install @feathersjs/socketio @feathersjs/koa --save

npx ts-node app.ts
```

## Run

Open `http://localhost:3030` in browser
