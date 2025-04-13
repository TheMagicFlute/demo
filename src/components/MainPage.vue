<template>
  <div class="greeting">
    <h1 class="green" id="title">Hi from TheMagicFlute!</h1>
    <h3>
      This is my Vue3 page demo.
      <br />
      Old page at <a href="https://themagicflute.github.io/">themagicflute.github.io</a>.
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greeting h1,
.greeting h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greeting h1,
  .greeting h3 {
    text-align: left;
  }
}
</style>
