<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <HeaderComp/>
  <HeaderBannerComp/>
  <BlogDetailsPage/>
  <HomePage/>
  <BlogPage/>
  <FooterComp/>
  <ProductDetails/>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue' 
import HeaderComp from './components/HeaderComp.vue'
import HeaderBannerComp from './components/HeaderBannerComp.vue'
import BlogDetailsPage from './components/BlogDetailsPage.vue'
import BlogPage from './components/BlogPage.vue'
import FooterComp from './components/FooterComp.vue'
import ProductDetails from './components/ProductDetails.vue'
import HomePage from './components/HomePage.vue'

export default {
  name: 'App',
  components: {
    BlogDetailsPage,
    BlogPage,
    HeaderComp,
    HeaderBannerComp,
    FooterComp,
    ProductDetails,
    HomePage
}
}
</script>

<style lang="scss">
* {
   margin: 0;
   padding: 0;
}
.center {
   padding-left: calc(50% - 1240px / 2);
   padding-right: calc(50% - 1240px / 2);
}
a {
   text-decoration: none;
}
</style>
