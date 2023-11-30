<template>
	<div class="h-full flex flex-col gap-10 items-center py-12">
		<address class="flex flex-col items-center gap-1 p-5 not-italic">
			<i class="fas fa-user-circle text-6xl p-2"></i>
			<p>JOHN DON</p>
			<p>Email: <a href="mailto:contato@exemplo.com">Johndon@company.com</a></p>
		</address>
		<nav class="flex flex-col gap-10">
			<a href="#"><i class="fas fa-house text-base pr-2"></i>home </a>
			<a href="#"><i class="fas fa-file text-base pr-2"></i>File </a>
			<a href="#"><i class="fas fa-message text-base pr-2"></i>Message </a>
			<a href="#"><i class="fas fa-bell text-base pr-2"></i>Notification</a>
			<a href="#"><i class="fas fa-location text-base pr-2"></i>Location</a>
			<a href="#"><i class="fas fa-chart-pie text-base pr-2"></i>Graph</a>
			
		</nav>
	</div>
</template>

<script>
export default {
	name: "Navegation",
};
</script>
