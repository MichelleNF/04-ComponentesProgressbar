<template>
  
  <div class="container mt-3">  
    <Header/>
    <Formulario/>
    <!-- para que los datos no se refresquen utilizamos eso <comentario-->
  </div>
</template>

<script>
  import Header from './assets/components/Header.vue';
  import Formulario from './assets/components/Formulario.vue';
  
  export default {
    components:{
    Header,
    Formulario,
    }
  }
</script>

<style scoped>
  div{
    margin: 0px, 2rem;
  }
</style>