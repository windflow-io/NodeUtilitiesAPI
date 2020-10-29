# Windflow Node API

Private Windflow API endpoints for doing stuff that is easier to do with Node.js than Java.

Post JSON body (below) to `http://auth.windflow.io.local:5000/compile-vue-sfc`
```json
{"name":"Mark.vue", "sfc":"<template><h1>Hello World</h1></template>"}
```


```bash
# Install dependencies.
npm install

# Start the webserver.
npm start
```
