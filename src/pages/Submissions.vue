<template>
  <Layout>
    <div class="submissions-title">
      <h1 class="submission-title__text">
        Submissions
      </h1>
    </div>

    <div class="submissions content-box">
      <div class="submissions__content">
        <p>Want to write for MAG MAG? Send us a pitch for an article at XXXXXXX.</p> 
        <p>We publish non-fiction from around the world about politics and society and deep dives into under-investigated bits of culture. We also accept submissions of fully written articles. We are explicitly leftist, and encourage communists, anarchists, and socialists of all (most) stripes to submit articles.</p>
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