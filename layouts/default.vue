<template>
	<div class="resp">
        <PicutureHigh />
		<Navbar />
		<main>
			<nuxt />
		</main>
		<Footer />
	</div>
</template>

<script>
    import PicutureHigh from "/components/PicutureHigh";
	import Navbar from "/components/Navbar"; // headerをインポート
	import Footer from "/components/Footer"; // footerをインポート

	export default {
		components: {
            PicutureHigh,
			Navbar,
			Footer,
		}
	};
</script>