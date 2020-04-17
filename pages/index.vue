<template>
  <div class="home">
    <img
      v-shared-element:vue-logo="{
        zIndex: 2
      }"
      src="https://vuejs.org/images/logo.png"
      alt="Vue.js logo"
    />
    <h1>v-shared-element</h1>
    <h3>Declarative shared-element transitions for Vue.js</h3>

    <nuxt-link v-shared-element:install class="button" to="/install"
      >Installation</nuxt-link
    >
    <nuxt-link v-shared-element:usage to="/usage"
    >
    <img src="https://i.ytimg.com/vi/MPV2METPeJU/maxresdefault.jpg">
    </nuxt-link>
  </div>
</template>

<style lang="scss" scoped>
.home {
  margin: var(--sizing--5x) 20%;
}
img {
  height: 150px;
}
.button {
  width: 100%;
  height: 70px;
  display: flex;
  color: #fff;
  text-decoration: none;
  font-family: inherit;
  font-size: 1.25rem;
  justify-content: center;
  align-items: center;
  margin: var(--sizing--3x) 0;
  border-radius: 24px;
  background: #2e586b;
  &:hover {
    background: hsl(199, 30%, 35%);
  }
}
</style>