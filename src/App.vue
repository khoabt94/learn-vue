<script lang="ts">
import Button from './components/Button.vue'
import Title from './components/Title.vue'
export default {
    name: 'App',
    components: {
      Button,
      Title
    },
    data() {
      return {
        name: 'Khoa',
        title: 'login',
        showTitle: false
      }
    },
    methods: {
      toggleShow() {
        this.showTitle = !this.showTitle
      }
    }
}
</script>

<template>
  <h1>Hello World {{ name }}</h1>
  <Button variant="danger" :onClick="toggleShow" >
    <p>{{title}}</p>
  </Button>
  <Title :title="title" :show="showTitle"/>
</template>

<style>

</style>
