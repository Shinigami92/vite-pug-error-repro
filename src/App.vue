<template lang="pug" src="./App.pug"></template>

<script lang="ts">
import logo from '@/assets/logo.png';
import { defineComponent } from '@vue/composition-api';
import HelloWorld from '@/components/HelloWorld.vue';

export default defineComponent({
  name: 'App',
  components: {
    HelloWorld
  },
  setup() {
    return { logo };
  },
  created() {
    console.log(logo);
  }
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
