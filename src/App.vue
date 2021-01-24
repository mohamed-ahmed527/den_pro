<template>
  <div id="app">

    <Navbar/>
    <Header/>
    <About/>
    <Products/>
    <Gallery/>
    <Getintouch/>
    <div class="map">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d158858.47340002653!2d0.03848390642535557!3d51.52855824164916!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47d8a00baf21de75%3A0x52963a5addd52a99!2z2YTZhtiv2YbYjCDYp9mE2YXZhdmE2YPYqSDYp9mE2YXYqtit2K_YqQ!5e0!3m2!1sar!2seg!4v1611508894940!5m2!1sar!2seg" width="100%" height="450" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
  </div>
  <Contact/>
    <router-view />
  </div>
</template>
<script>
import Navbar from"./components/Navbar.vue";
import Header from"./components/Header.vue";
import About from"./components/About.vue";
import Products from './components/Products.vue';
import Gallery from './components/Gallery.vue';
import Getintouch from"./components/Getintouch.vue";
import Contact from"./components/Contact.vue";
export default {
  name:"app",
  components: {Navbar,Header,About,Products, Gallery,Getintouch,Contact}
}
</script>
<style lang="scss">
.map{
  width: 100%;
}
.container{
  width: 80%;
  margin: auto;
}
body{
  margin: 0px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>
