# sql-editor Performance

This repo contains an online SQL editor that comes with predefined queries and filter functionalities. It was built with Nuxt.js

Demo can be found on [https://sql-editor-test.netlify.app/](https://sql-editor-test.netlify.app/)


Web.dev: [Performance Score](https://lighthouse-dot-webdotdevsite.appspot.com//lh/html?url=https%3A%2F%2Fsql-editor-test.netlify.app%2F)

GT Metrix: [Performance Score](https://gtmetrix.com/reports/sql-editor-test.netlify.app/mqeRjrdc/)

Google Chrome Lighthouse
![performance screenshot](https://github.com/Timibadass/sql-editor/blob/master/assets/images/Screenshot%202021-06-06%20at%2001.51.49.png)

## Page Load Time
```
The Page load time of the application was calculated using google chrome's lighthouse feature, GT METRIX, and web.dev.
```
### Steps Taken to improve load time
```
1. Using [Vue lazy hydrate](https://yarnpkg.com/package/vue-lazy-hydration) to hydrate certain components to improve Time to Interaction.
```
### Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).
# Atlan
