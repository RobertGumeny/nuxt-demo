<template>
  <div class="container">
    <div class="hero">
      <h1 class="title">
        NuxtJS Demo
      </h1>
      <h3 class="subtitle">A brief demo of Vue and NuxtJS</h3>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a>
      </div>
      <div class="row">
        <Process />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  padding-top: 25vh;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 6.5rem;
  color: $color-primary;
  letter-spacing: 1px;
}

.row {
  margin: 11rem 0 4rem 0;
}

.subtitle {
  font-weight: 300;
  font-size: 2.5rem;
  color: $color-secondary-light;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
