<template>
  <div>
    <SiteHeader />
    <Nuxt />
    <BottomNav />
    <SiteFooter />
  </div>
</template>

<style lang="scss">
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid $color-primary-light;
  color: $color-primary;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: $color-white;
  background-color: $color-primary;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid $color-secondary;
  color: $color-secondary;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: $color-secondary;
}
</style>
