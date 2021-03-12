<template lang="pug" src="./App.pug"></template>

<script lang="ts">
import logo from '@/assets/logo.png';
import { defineComponent } from '@vue/composition-api';

export default defineComponent({
  name: 'App',
  setup() {
    return { logo };
  },
  created() {
    console.log(logo);
  }
});
</script>
