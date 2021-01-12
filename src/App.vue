<template>
  <div id="app">
    <MainPage msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import MainPage from './components/MainPage.vue'
import '../src/scss/app.scss';

export default {
  name: 'App',
  components: {
    MainPage
  }
}
</script>
