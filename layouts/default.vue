<template>
  <div>
    <header-component></header-component>
    <offcanvas-component></offcanvas-component>
    <section class="container-wrap">
      <nuxt />
    </section>
    <footer-component></footer-component>
  </div>
</template>

<script>
import HeaderComponent from '../components/header.vue';
import OffcanvasComponent from '../components/offcanvas.vue';
import footerComponent from '../components/footer.vue';

export default {
  components:{
    HeaderComponent, OffcanvasComponent, footerComponent
  }
}
</script>

<style>
</style>
