<template>
  <div>
    <app-header></app-header>
    <app-body></app-body>
    <app-footer></app-footer>
  </div>
</template>

<script>
import Header from './components/header'; 
import Footer from './components/footer';
import Body from './components/body';
export default {
  components:{
    'app-header':Header,
    'app-footer': Footer,
    'app-body': Body
  },

  data () {
    return {
     
    }
  }
}
</script>

<style>

</style>
