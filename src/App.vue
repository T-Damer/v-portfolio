<template>
  <Home msg="Welcome to v-portfolio" />
</template>

<script>
import Home from './components/Home.vue'

export default {
  name: 'VP 📟',
  components: {
    Home,
  },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@100;400;900&display=swap');

:root {
  --hue-color: 291; /* Pink - 335, Blue - 240, Green - 154, Orange - 25 */
  --first-color: hsl(var(--hue-color), 53%, 49%);
  --title-color: hsl(var(--hue-color), 53%, 15%);
  --text-color: hsl(var(--hue-color), 12%, 35%);
  --text-color-light: hsl(var(--hue-color), 12%, 65%);
  --white-color: #fff;
  --body-color: hsl(var(--hue-color), 24%, 94%);
}

/*===== Typography =====*/
:root {
  --body-font: 'Lato', sans-serif;
  --big-font-size: 3rem;
  --small-font-size: 0.815rem;
  --smaller-font-size: 0.75rem;
  --tiny-font-size: 0.625rem;
  --font-medium: 1.2rem;
}

@media screen and (min-width: 968px) {
  :root {
    --big-font-size: 3.5rem;
    --small-font-size: 0.875rem;
    --smaller-font-size: 0.815rem;
    --tiny-font-size: 0.75rem;
  }
}

*,
*::before,
*::after {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

/*===== Border-radius =====*/
:root {
  --br-6: 6px;
}

/*===== Margin =====*/
:root {
  --mb-0-25: 0.25rem;
  --mb-1: 1rem;
  --mb-1-5: 1.5rem;
  --mb-2-5: 2.5rem;
}

body {
  margin: 0;
  font-family: var(--body-font);
  background-color: var(--body-color);
  color: var(--text-color);
}

img {
  height: auto;
}

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
