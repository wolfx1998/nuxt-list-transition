<template>
<div>
  <img v-shared-element:usage src="https://i.ytimg.com/vi/MPV2METPeJU/maxresdefault.jpg">
    <nuxt-link to="/">Go back</nuxt-link>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda cum ex ad modi ut accusamus id tempora, dolore commodi, ullam similique, aut autem impedit quaerat perspiciatis? Repellendus accusamus illo error.</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda cum ex ad modi ut accusamus id tempora, dolore commodi, ullam similique, aut autem impedit quaerat perspiciatis? Repellendus accusamus illo error.</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda cum ex ad modi ut accusamus id tempora, dolore commodi, ullam similique, aut autem impedit quaerat perspiciatis? Repellendus accusamus illo error.</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda cum ex ad modi ut accusamus id tempora, dolore commodi, ullam similique, aut autem impedit quaerat perspiciatis? Repellendus accusamus illo error.</p>
</div>
</template>

<style lang="scss" scoped>
.home {
  padding: var(--sizing--5x) 0;
  width: 100%;
  height: 100%;
  min-height: 100vh;
}
.container {
  margin: 0 15%;
}
.button {
  width: 100%;
  height: 70px;
  display: flex;
  color: #fff;
  text-decoration: none;
  background: #2e586b;
  font-family: inherit;
  font-size: 1.25rem;
  justify-content: center;
  align-items: center;
  margin: var(--sizing--3x) 0;
  border-radius: 24px;
  &:hover {
    background: hsl(199, 30%, 35%);
  }
}
</style>