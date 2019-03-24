<template>
  <section>
    <main-slider></main-slider>
    <div class="container main">
      <h1 class="title">
        temamoaVue
      </h1><br>
      이제 개발환경이 구축 되었다!<br>
      <nuxt-link to="/about">about</nuxt-link>
    </div>
  </section>
</template>

<script>
import MainSlider from '../components/MainSlider.vue'

export default {
  components: {
    MainSlider
  }
}
</script>

<style>
.main {
  min-height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>