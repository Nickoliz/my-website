<template>
  <div>
    <div class="hello">Hello</div>
    <transition name>
      <img id="profile-photo" src="../assets/nick-b.jpg" />
    </transition>
  </div>
</template>

<script>
import "../scss/mainpage.scss";

export default {
  name: "MainPage",
  props: {
    msg: String,
  },
};
</script>
