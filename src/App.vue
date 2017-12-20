<template>
  <div class="container">
    <app-header></app-header>
    <div class="row">
      <app-serverList></app-serverList>
      <app-serverDetails></app-serverDetails>      
    </div>
    <hr>
    <app-footer></app-footer>
  </div>
</template>

<script>
  import Header from "./components/Shared/Header.vue";    
  import Footer from "./components/Shared/Footer.vue";
  import ServerList from "./components/Server/ServerList.vue";
  import ServerDetails from "./components/Server/ServerDetails.vue";  

  export default {
    components: {
      'app-header': Header,
      'app-serverList': ServerList,
      'app-serverDetails': ServerDetails,
      'app-footer': Footer
    }
  }
</script>

<style>

</style>
