<template>
    <b-nav card-header tabs>
        <!-- <b-nav-item>'s with child routes. Note the trailing slash on the first <b-nav-item> -->
        <b-nav-item to="/" exact exact-active-class="active">Inicio</b-nav-item>
        <b-nav-item to="/registro" exact exact-active-class="active">Registro</b-nav-item>
        <b-nav-item to="/convocatorias" exact exact-active-class="active">Convocatorias</b-nav-item>
        <b-nav-item to="/habilitados" exact exact-active-class="active">Habilitados</b-nav-item>
        <b-nav-item to="/about" exact exact-active-class="active">Acerca de ...</b-nav-item>
      </b-nav>
</template>

<script>
  export default{
    name:"MenuPub"
  }
</script>

<style>

</style>