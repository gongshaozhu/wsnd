<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <div>
    <img src="./assets/a.png" alt="" @click="click">
    <h1 style="font-size: 100px">{{d}}</h1>
  </div>
</template>
<script>
export default {
  data: () => {
    return {
      d: ''
    }
  },
  methods: {
    click() {
      this.d = '我是你爹！！！ --龚少竹'
    }
  }
}
</script>
<style scoped>

</style>
