<template>
		<header>
            <nav>     
                <div className="flex-container">           
                        <ul>
                            <li><NuxtLink to="/" class="hvv">Home</NuxtLink></li>
                            <li><NuxtLink to="about" class="hvv">About</NuxtLink></li>
                            <li><NuxtLink to="career" class="hvv">Career</NuxtLink></li>
                            <li><NuxtLink to="access" class="hvv">Access</NuxtLink></li>
                            <li><NuxtLink to="active" class="hvv">Active Log</NuxtLink></li>
                            <li><a href="https://opepelab.org/"><a target="brank">News Blog</a></a></li>
                        </ul>
                </div>
            </nav>    
        </header>
</template>

<script>
	import Navbar from "@/components/Navbar.vue";
	export default {
		components: {
			Navbar
		}
	};
</script>