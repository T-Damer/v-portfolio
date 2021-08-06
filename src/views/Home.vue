<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <Section msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import Section from '@/components/Section.vue'

export default {
  name: 'Home',
  components: {
    Section,
  },
}
</script>
