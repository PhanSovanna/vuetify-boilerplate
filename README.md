# Vuetify Boilerplate

Vuetify Boilerplate is built upon the [Vuetify SSR Webpack Template](https://vuetifyjs.com/en/guides/server-side-rendering).

The frontend was built using the [Vue-Hackernews-2.0 Template](https://github.com/vuejs/vue-hackernews-2.0), and uses [vue-router](https://router.vuejs.org/) and [vuex](https://vuex.vuejs.org/), with [server-side rendering](https://ssr.vuejs.org/en/); vue-router and vuex store are kept in sync using [vuex-router-sync](https://github.com/vuejs/vuex-router-sync).

## Features

> Note: in practice, it is unnecessary to code-split for an app of this size (where each async chunk is only a few kilobytes), nor is it optimal to extract an extra CSS file (which is only 1kb) -- they are used simply because this is a demo app showcasing all the supported features. In real apps, you should always measure and optimize based on your actual app constraints.

- Server Side Rendering
  - Vue + vue-router + vuex working together
  - Server-side data pre-fetching
  - Client-side state & DOM hydration
  - Automatically inlines CSS used by rendered components only
  - Preload / prefetch resource hints
  - Route-level code splitting
- Progressive Web App
  - App manifest
  - Service worker
  - 100/100 Lighthouse score
- Single-file Vue Components
  - Hot-reload in development
  - CSS extraction for production
- Animation
  - Effects when switching route views
  - Real-time list updates with FLIP Animation

## Architecture Overview

<img width="973" alt="screen shot 2016-08-11 at 6 06 57 pm" src="https://cloud.githubusercontent.com/assets/499550/17607895/786a415a-5fee-11e6-9c11-45a2cfdf085c.png">

**A detailed Vue SSR guide can be found [here](https://ssr.vuejs.org).**

## Pre-setup

``` bash
#clone original repo
git clone https://github.com/vuetifyjs/webpack-ssr.git

#create instance template
vue init vuetifyjs/webpack-ssr ../vuetify-boilerplate

#go to root
cd ../vuetify-boilerplate

# install dependencies
sudo npm install

# serve with hot reload at localhost:8080
npm run dev

```

## Build

``` bash
#clone this repo
git clone https://github.com/chuycepeda/vuetify-boilerplate.git

#go to root
cd vuetify-boilerplate

# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

```

## License

[MIT](http://opensource.org/licenses/MIT)

For additional information, please visit the [Official Documentation](https://vuetifyjs.com).
