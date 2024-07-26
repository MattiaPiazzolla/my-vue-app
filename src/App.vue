<script>
// importo il titolo dall'app apptitle
  import appTitle from './components/AppTitle.vue'
  import AppImg from './components/AppImg.vue';

  // lo abilito all'utilizzo 
  export default{
    components:{
      appTitle,
      AppImg
    }
  }
</script>

<template>
 <header>
  <appTitle />
 </header>
 <main>
  <AppImg />
 </main>
</template>

<style>
  header{
    background-color: rgb(0, 0, 0);
  }
  main{
    padding-top: 5%;
    display: flex;
    justify-content: center;
  }
</style>
