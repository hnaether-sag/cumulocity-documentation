# Documentation Demo

This project uses https://github.com/compodoc/compodoc in order to generate a documentation web app.
Documentation of the plugin can be found at https://compodoc.app/guides/getting-started.html.
---

## Setup

1. run `npm install` to install the dependencies for the demo.
2. run `npm start` to start local dev server with proxy.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.1.

## Generate documentation
Run `npm run generate-docs` in order to run compodoc which will generate a documentation folder under dist.

## Deploy documentation
This step requires that `npm run generate-docs` was already run. Run `npm run deploy-docs` in order to create a new webapp and deploy it to a tenant of your liking. You can edit the cumulocity.json.doc to change metadata for the documentation webapp. You can also edit the script-command in the package.json to change the tenant endpoint.