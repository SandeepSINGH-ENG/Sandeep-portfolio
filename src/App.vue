
<template>
  <div id="app">
     <Header/>
     <main>
      <router-view></router-view>
     </main>
     <Footer/>
  </div>
    
</template>

<script>
import Header from './components/header.vue';
import Footer from './components/Footer.vue';
export default {
  name: 'App',
  components: {
    Header,
    Footer
  }
};
</script>

<style>
/* Add your styles here */
</style>
