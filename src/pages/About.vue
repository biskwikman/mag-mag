<template>
  <Layout>
    <div class="submissions-title">
      <h1 class="submission-title__text">
        Submissions
      </h1>
    </div>

    <div class="submissions content-box">
      <div class="submissions__content">
        <p>
          MAG MAG Magazine is the world's premier "magazine" for leftist/misc. articles that other, actually known outlets won't publish.
          Right now those are all by me - Dan Henri. I also made the site.
        </p>
        <p>Want to write for MAG MAG for some reason? Send me a pitch for an article at djosephhenri[at]gmail[dot]com.</p> 
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