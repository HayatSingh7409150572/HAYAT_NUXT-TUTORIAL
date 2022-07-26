<template>
  <h>Routing
Most websites have more than just one page. For example a home page, about page, contact page etc. In order to show these pages we need a Router.

Automatic Routes
Most websites will have more than one page (i.e. a home page, about page, contact page etc.). In order to show these pages, we need a Router. That's where vue-router comes in. When working with the Vue application, you have to set up a configuration file (i.e. router.js) and add all your routes manually to it. Nuxt automatically generates the vue-router configuration for you, based on your provided Vue files inside the pages directory. That means you never have to write a router config again! Nuxt also gives you automatic code-splitting for all your routes.

In other words, all you have to do to have routing in your application is to create .vue files in the pages folder.</h>
  <div>
  <h1>{{title}}</h1>
  </diV>
</template>

<script>
export default{
  head(){
    return {
      title:"BOOOM"
    }
  }
}
</script>