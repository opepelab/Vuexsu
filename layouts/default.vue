<template>
	<div>
        <PicutureHigh />
		<Navbar />
		<main>
			<nuxt />
		</main>
		<Footer />
	</div>
</template>

<script>
    import PicutureHigh from "/components/picuturehigh.vue";
	import Navbar from "/components/navbar.vue"; // headerをインポート
	import Footer from "/components/footer.vue"; // footerをインポート

	export default {
		components: {
            PicutureHigh,
			Navbar,
			Footer
		}
	};
</script>