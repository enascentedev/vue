<script setup>
import Cabecalho from "../components/cabecalho.vue";
import Count from "../components/count.vue";
import Dashboard from "../components/dashboard.vue";
import Navegation from "../components/navegation.vue";
</script>

<template>
	<header>
<cabecalho/>
	</header>
	<main>
		<count/>
		<aside>
			<navegation />
		</aside>
		<dashboard/>
	</main>
</template>
