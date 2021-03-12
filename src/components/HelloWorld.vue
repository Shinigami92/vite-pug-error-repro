<template lang="pug" src="./HelloWorld.pug"></template>

<script lang="ts">
import { ref, defineComponent } from '@vue/composition-api';
export default defineComponent({
  name: 'HelloWorld',
  props: {
    msg: {
      type: String,
      required: true
    }
  },
  setup() {
    const count = ref(0);
    return { count };
  }
  // data: () => ({ count: 0 })
});
</script>

<style scoped>
a {
  color: #42b983;
}

label {
  margin: 0 0.5em;
  font-weight: bold;
}

code {
  background-color: #eee;
  padding: 2px 4px;
  border-radius: 4px;
  color: #304455;
}
</style>
