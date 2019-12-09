<template>
	<div class="author">

		<h1 v-if="showTitle" class="author__site-title">
			{{ $static.metadata.siteName }}
		</h1>

		<p class="author__intro">
			<em>{{ $static.metadata.siteDescription }}</em>
		</p>

		<p class="author__links">
			<g-link to="/subscribe"><t>Subscribe!</t></g-link>
			|
			<g-link to="/submissions"><t>Submissions</t></g-link>
		</p>

	</div>
</template>

<static-query>
query {
  metadata {
    siteName
	siteDescription
  }
}
</static-query>

<script>
export default {
	props: ['showTitle']
}
</script>

<style lang="scss">
.author {
	margin: 0 auto;
	max-width: 500px;
	text-align: center;
	padding: calc(var(--space) / 2) 0;

	&__intro {
		opacity: .8;
	}

	&__site-title {
		font-size: 4em;
	}

	&__links {
		margin-top: -.5em;
		t {
			margin: 0 .5em;
		}
	}
}
</style>
