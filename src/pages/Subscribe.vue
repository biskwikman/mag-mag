<template>
  <Layout>
    <div class="subscribe-title">
      <h1 class="subscribe-title__text">
        Subscribe
      </h1>
    </div>

    <div class="subscribe content-box">
      <div class="subscribe__content">
        <p>Contribute to my <a href="https://www.patreon.com/magmag">Patreon</a> to help me produce new articles and grow MAG MAG! All funds go to paying writers and website maintenance.</p>
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