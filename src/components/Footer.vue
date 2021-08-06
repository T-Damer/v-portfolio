<template>
  <footer class="footer__container">
    <div class="footer__logo">
      <h1>Say hello</h1>
    </div>
    <div class="footer__nav">
      <div class="footer__item">
        HOME
      </div>
      <div class="footer__item">
        Fresh
      </div>
      <div class="footer__item">
        Creativity
      </div>
    </div>
    <div class="footer__socials">
      <box-icon name="bulb"></box-icon>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.footer__container {
  display: flex;
  flex-direction: row;
}

.footer__nav {
  display: flex;
  flex-direction: row;
}

.footer__socials {
}
</style>
