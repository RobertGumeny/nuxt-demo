<template>
  <nav>
    <nuxt-link to="/" class="logo">Nuxt<span class="logo-secondary">JS</span></nuxt-link>
    <ul>
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/about">About</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/contact">Contact</nuxt-link>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "navbar"
}
</script>

<style lang="scss" scoped>
  nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 1em;
    background: $color-primary;

    .logo {
      font-size: 2rem;
    }

    a {
      font-weight: normal;
      text-decoration: none;
      padding: 0.5rem;
      color: $color-white;
      cursor: pointer;
    }

    ul {
      list-style: none;
      padding: 0;
      display: flex;

      a {
        font-size: 1.25rem;
      }
    }
  }
</style>