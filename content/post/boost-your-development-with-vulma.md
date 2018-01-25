+++
date = "2018-1-25T70:00:55+02:00"
draft = false
title = "Boost your development by using Vulma."

+++

If you make tailored web applications like we do @nbhood, you often find yourself facing the same problems for most of the applications.

For example, REST API integration, localization, analytics, social sharing, local storage and store managment to name a few. not only that some logic is almost wanted by all our clients, but also some of common UI components are required such modals, accordions and so on.

We thought that it would be very nice if we can start diving straight to the tailored stuff and have everything else already written for us. So we made our bolier plate [vulma] to cut down this time.

Super powers at npm install !

* Core 
  * webpack + vue-loader + hotreloading + linting + testing + css extractions
  * [vuex](https://github.com/vuejs/vuex)
  * [vue-router](https://github.com/vuejs/vue-router)
  * [vue-local-storage](https://github.com/pinguinjkeke/vue-local-storage)
  * [vue-i18n](https://github.com/kazupon/vue-i18n)
  * [vuex-rest-api](https://github.com/christianmalek/vuex-rest-api)
* Plugins
  * [vue-awesome](https://github.com/Justineo/vue-awesome)
  * [vue-carousel](https://github.com/SSENSE/vue-carousel)
  * [favicons-webpack-plugin](https://github.com/jantimon/favicons-webpack-plugin)
  * [vue-social-sharing](https://github.com/nicolasbeauvais/vue-social-sharing)
  * [vue-google-maps](https://github.com/xkjyeah/vue-google-maps)
  * [vue-time-ago](https://github.com/egoist/vue-timeago)
  * [vue2-filters](https://github.com/freearhey/vue2-filters)
  * [vue-paginate](https://github.com/TahaSh/vue-paginate)
  * [vue-analytics](https://github.com/MatteoGabriele/vue-analytics)
  * [vue-multiselect](https://github.com/monterail/vue-multiselect)
* Directives
  * [vue-scrollto](https://github.com/rigor789/vue-scrollTo)
  * background 
* Components
  * Application loading
  * Loading
  * Page Header

In addition to all these goodies, Vulma uses a nice application structure and shows a proper way use vuex and layout your pages and componenets.
So Far, we've covered all the javascript powerups. As for the CSS, we often find ourseleves using some css framework in order not to rerwrite everything we Added Bulma to Vulma's core so that it's avaiable out of the box.

We've also added some helper methods that are not avaiable in Bulma so that you get more powers.

We still plan to add more features that we think are commonly required such as authentication, animation, form validations and server side rendering.



