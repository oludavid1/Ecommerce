<template>
   <v-app>
    <NavbarPage class="index" />
    <DashBoard />
    <FooterPage />
  </v-app>
</template>

<script>
  import NavbarPage from '../components/NavbarPage'
  import DashBoard from '../components/DashBoard'
  import FooterPage from '../components/FooterPage'

  export default {
    name: 'HomeView',

    components: {
      NavbarPage,
      DashBoard,
      FooterPage
    },
  }
</script>

<style scoped>
.index{
  z-index: 9999;
}
</style>
