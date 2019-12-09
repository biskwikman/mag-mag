<template>
  <Layout>
    <div class="submissions-title">
      <h1 class="submission-title__text">
        Submissions
      </h1>
    </div>

    <div class="submissions content-box">
      <div class="submissions__content">
        <p>Want to write for MAG MAG? Send us an pitch for an article at XXXXXXX.</p> 
        <p>We publish non-fiction about leftist politics and deep dives into under-appreciated cultural artifacts. We also accept submissions of fully written articles.</p>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
    
}
</script>

<style lang="scss">
.submissions-title {
  padding: calc(var(--space) / 2) 0 calc(var(--space) / 2);
  text-align: center;
}

.submissions {
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