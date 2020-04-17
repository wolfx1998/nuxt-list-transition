<template>
  <div v-shared-element:install class="home">
    <img
      v-shared-element:vue-logo
      src="https://vuejs.org/images/logo.png"
      alt="Vue.js logo"
    />
    <h1>Installation</h1>
    <h2>npm</h2>
    <nuxt-link to="/" class="button">Close</nuxt-link>
  </div>
</template>

<style lang="scss" scoped>
.home {
  padding: var(--sizing--5x) 15%;
  width: 100%;
  height: 100%;
  min-height: 100vh;
  background: hsl(199, 40%, 30%);
}
.button {
  width: 75%;
  height: 70px;
  display: flex;
  color: #fff;
  text-decoration: none;
  font-family: inherit;
  font-size: 1.25rem;
  justify-content: center;
  align-items: center;
  margin: var(--sizing--4x) auto;
  border-radius: 24px;
  background: hsl(148, 24%, 49%);
  &:hover {
    background: hsl(148, 25%, 55%);
  }
}
</style>