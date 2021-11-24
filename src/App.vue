<template>
  <div id="app">
    <!-- HEADER -->
    <Header/>

    <!-- MAIN -->
    <main>
      <Content/>
      <Mainextra/>
    </main>

    <!-- FOOTER -->
    <footer>
      <Footernav/>
      <Footerfollow/>
    </footer>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Content from './components/Content.vue';
import Mainextra from './components/Mainextra.vue';
import Footernav from './components/Footernav.vue';
import Footerfollow from './components/Footerfollow.vue';

export default {
  name: 'App',
  components: {
    Header,
    Content,
    Mainextra,
    Footernav,
    Footerfollow
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
