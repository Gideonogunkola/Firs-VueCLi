<template>
 <div id = "ninjas">
     <ul>
         <li v-for="ninja in ninjas" @click="ninja.show = !ninja.show" :key="ninja.name">
            <h2>{{ninja.name}}</h2> 
            <h3 v-show="ninja.show">{{ninja.speciality}}</h3>
         </li>
     </ul>

 </div>
</template>

<script>
export default {
 
  data () {
    return {
    ninjas:[
        {name: 'Gideon', speciality:'Vue components', show:false},
        {name: 'Godwin', speciality:'HTML Wizard', show:false},
        {name: 'Jedi', speciality:'Clicks Events', show:false},
        {name: 'Tayo', speciality:'Conditionals', show:false},
        {name: 'Gbemi', speciality:'Webpack', show:false},
        {name: 'Isreal', speciality:'Data Digging', show:false},
    ]
    }
  }
}
</script>

<style scoped>
   #ninja{
       width:100%;
       max-width: 1200pc;
       margin: 40px auto;
       padding: 0 20px;
       box-sizing: border-box;
   } 

   ul{
       display: flex ;
       flex-wrap: wrap;
       list-style-type: none;
       padding: 0;
   }
   li{
       flex-grow:1;
       flex-basis: 300px;
       text-align: center;
       padding: 30px;
       border: 1px solid #222;
       margin:10px;
   }
</style>
