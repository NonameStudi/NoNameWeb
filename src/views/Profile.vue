<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <Profile msg="Welcome to Your Vue.js + TypeScript App" />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import Profile from "../components/Profile.vue";

@Options({
  components: {
    Profile,
  },
})
export default class Home extends Vue {}
</script>
