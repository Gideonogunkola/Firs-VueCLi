<template>
  <header>
      <h1>{{ title }}</h1>
  </header>
</template>

<script>
export default {
  data () {
    return {
     title: 'First Vue-App'
    }
  }
}
</script>

<style scoped>
    header{
        background-color: brown;
        padding: 10px;
    }
    h1{
        color:cornsilk;
        text-align: center;
    }
</style>
