<template>
  <div class="footer">
    <footer>
      <nav>
        <ul>
          <li>
            <nuxt-link to="/">Home</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/">About</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/">Contact</nuxt-link>
          </li>
        </ul>
      </nav>
      <p><small>&copy; 2020 NuxtJS. All Rights Reserved.</small></p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "footer"
}
</script>

<style lang="scss" scoped>
  footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: $color-primary;
    color: white;
    padding: 1.5rem;

    nav ul {
      display: flex;
      justify-content: space-between;
      list-style: none;

      li a {
        color: $color-white;
        text-decoration: none;
        padding: 1rem;
        cursor: pointer;
      }
    }
  }
</style>