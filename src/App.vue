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
  import Header from "./Header.vue";    
  import ServerList from "./ServerList.vue";
  import ServerDetails from "./ServerDetails.vue";
  import Footer from "./Footer.vue";

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
