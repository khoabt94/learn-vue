<script lang="ts">
import Modal from './components/Modal.vue'
export default {
    name: 'App',
    components: {
      Modal,
    },
    data() {
      return {
        name: 'Khoa'
      }
    }
}
</script>

<template>
  <h1>Hello World {{ name }}</h1>
  <Modal/>
</template>

<style>

</style>
