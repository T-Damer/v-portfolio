<template>
  <section class="section home">
    <div>
      <h1>{{ msg }}</h1>
      <h2>{{ subMsg }}</h2>
    </div>
    <slot name="child-slot" class="home__children">
      <span v-html="children"></span>
    </slot>
  </section>
</template>

<script>
export default {
  name: 'Section',
  props: {
    msg: String,
    subMsg: String,
    children: String,
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.section {
  height: 100vh;
  margin: var(--mb-2-5) 0 0 var(--mb-2-5);
}
</style>
