<template>
  <nav class="nav__container">
    <div class="nav__logo">
      <h1>VP 📟</h1>
    </div>
    <div class="nav__items">
      <div class="nav__item">
        HOME
      </div>
      <div class="nav__item">
        Fresh
      </div>
      <div class="nav__item">
        Creativity
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Nav',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav__container {
  display: flex;
  flex-direction: row;
}

.nav__logo {
  margin-left: var(--m-2-5);
  width: 4rem;
  height: 4rem;
  background-color: var(--white-color);
  border-radius: 50%;
}

.nav__items {
  display: flex;
  flex-direction: row;
}
</style>
