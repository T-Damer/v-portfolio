<template>
  <nav class="nav__container">
    <div class="nav__logo">
      <h1>
        <router-link to="/">
          VP 📟
        </router-link>
      </h1>
    </div>
    <div class="nav__items">
      <div class="nav__item">
        <router-link to="/">
          HOME
        </router-link>
      </div>
      <div class="nav__item">
        <router-link to="/fresh">
          Fresh
        </router-link>
      </div>
      <div class="nav__item">
        <router-link to="/fresh">
          Creativity
        </router-link>
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
