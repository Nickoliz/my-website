<template>
  <div id="app">
    <MainPage msg="Welcome to Your Vue.js App" />
    <YourName msg="You are visiting my website."/>
  </div>
</template>
<script src="https://cdn.jsdelivr.net/npm/vue@2.6.12/dist/vue.js"></script>
<script>
import MainPage from "./components/MainPage.vue";
import YourName from "./components/YourName.vue";
import "../src/scss/app.scss";

export default {
  name: "App",
  components: {
    MainPage,
    YourName,
  },
};
</script>
