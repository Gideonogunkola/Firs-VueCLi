<template>
   <footer>
        <p> {{ copyright }}</p>
    </footer>
</template>

<script>
export default {
 
  data () {
    return {
     copyright: "Copyright 2021 Gideon Ogunkola"
    }
  }
}
</script>

<style scoped>
    footer{
       background: #000; 
       padding: 6px;
    }
    p{
        color:#fff;
        text-align: center;
    }
</style>
