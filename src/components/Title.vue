<template>
  <h1 :class="{ 'block': show, 'hidden' : !show }">
    {{title}}
  </h1>
</template>

<script>
  export default {
    name: 'Title',
      props: ['title', 'show']
  }
</script>

<style lang="scss" scoped>

</style>