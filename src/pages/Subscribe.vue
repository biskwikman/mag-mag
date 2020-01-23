<template>
  <Layout>
    <div class="subscribe-title">
      <h1 class="subscribe-title__text">
        Subscribe
      </h1>
    </div>

    <div class="subscribe content-box">
      <div class="subscribe__content">
        <p>Contribute to our <a href="https://www.patreon.com/magmag">Patreon</a> help us produce new articles! All funds go to future writers!</p>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
    
}
</script>

<style lang="scss">
.subscribe-title {
  padding: calc(var(--space) / 2) 0 calc(var(--space) / 2);
  text-align: center;
}

.subscribe {
  &__content {
    h2:first-child {
      margin-top: 0;
    }

    p:first-of-type {
      font-size: 1.2em;
      color: var(--title-color);
    }
  }
}

</style>