<template>
  <main>
    <h1>Home page</h1>
    <NuxtLink to="/about">
      About (internal link that belongs to the Nuxt App)000
    </NuxtLink>
    <a href="https://nuxtjs.org">External Link to another page</a>
  </main>
</template>

<script>
	export default {
		head: {
      title: 'Career - S.watana',
      meta: [
        {
          name:'description',
          content:'キャリアのページです',
        }
      ],
		}
	}
</script>