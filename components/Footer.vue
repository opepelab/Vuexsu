<template>
        <div>
            <footer>
                <div class="flex-container">                      
                        <Img class="maru static" src="/SVG/vue.svg" width="50" height="50" />
                        <table width="2%"></table>
                        <Img class="maru static" src="/SVG/nuxt.svg" width="50" height="50" />
                        <table width="2%"></table>
                        <Img class="maru static" src="/SVG/html5.svg" width="50" height="50" />
                        <table width="2%"></table>
                        <Img class="maru static" src="/SVG/css3.svg" width="50" height="50" />
                        <table width="2%"></table>
                        <Img class="maru static" src="/SVG/python3.svg" width="50" height="50" />
                </div>
                <h5>Copyright 2021 <a href="mailto:ocelot2828@gmail.com">su</a> inc.</h5>
            </footer>
        </div>
</template>

<script>
	import Footer from "@/components/Footer.vue";
	export default {
		components: {
			Footer
		}
	};
</script>