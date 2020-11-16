# Windflow Node Utilities API
## These utilities compile Vue 3 Single File Components into js files. CSS Purge API coming soon.
Part of the Windflow EternalEngine platform, commercially hosted at https://windflow.io. Email support@windflow.io with questions or queries - or to support these projects.

Post JSON body (below) to `http://localhost:5000/compile-vue-sfc`
```json
{"name":"MySingleFileComponent.vue", "sfc":"<template><h1>Hello World</h1></template>"}
```

```bash
# Install dependencies.
npm install

# Start the webserver.
npm start
```
