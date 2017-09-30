<template>

  <section class="container">
      <header-tom></header-tom>
    <div>
      <logo/>
      <h1 class="title">
        tomheld
      </h1>
      <h2 class="subtitle">
        architekten & ingenieure
      </h2>
      <div class="links">
        <a href="https://github.com/wuwu/tomheld" target="_blank" class="button--grey">GitHub</a>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'
import HeaderTom from '~/components/HeaderTom.vue'
export default {
  components: {
    Logo,
    HeaderTom
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
