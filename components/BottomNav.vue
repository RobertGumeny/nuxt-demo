<template>
  <nav>
    <ul>
      <li>
        <nuxt-link
          tag="img"
          :src="require('~/assets/images/dental.png')"
          to="/dental"
        ></nuxt-link>
      </li>
      <li>
        <nuxt-link
          tag="img"
          :src="require('~/assets/images/ocular.png')"
          to="/ocular"
        ></nuxt-link>
      </li>
      <li>
        <nuxt-link
          tag="img"
          :src="require('~/assets/images/medical.png')"
          to="/medical"
        ></nuxt-link>
      </li>
      <li>
        <nuxt-link
          tag="img"
          :src="require('~/assets/images/aesthetic.png')"
          to="/aesthetic"
        ></nuxt-link>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "bottomNav"
};
</script>

<style lang="scss" scoped>
nav ul {
  display: flex;
  justify-content: space-around;
  list-style: none;

  li img {
    cursor: pointer;
  }
}
</style>
