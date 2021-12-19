<template>
  <div id="app">
    <Header></Header>
    <Menu></Menu>
    <Home></Home>
    <router-view/>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Menu from '@/components/Menu.vue';
import Home from '@/components/Home.vue';
import Footer from '@/components/Footer.vue';
export default {
  name: "App",
  components: {
    Header,
    Menu,
    Home,
    Footer,
  }
}
</script>

<style scoped>

</style>