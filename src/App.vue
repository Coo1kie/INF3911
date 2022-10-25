<template>
  <div id="app">
    <div class="container">
      <img src="@/assets/bannerV.jpg" alt="" id="banner">
    
  <b-card title="Card Title" no-body>
    <b-card-header header-tag="nav">
      <menu-pub></menu-pub>
    </b-card-header>

    <b-card-body>
     
      <router-view></router-view>
     
    </b-card-body>
  </b-card>
</div>
    
   <!--<router-view/>--> 
  </div>
</template>
<script>
  
import MenuPub from './components/MenuPub.vue'
  export default{
    components:{
    MenuPub

    }
  }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
#banner{
  
}
</style>
