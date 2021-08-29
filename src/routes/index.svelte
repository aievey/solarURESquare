<script>
	import Cover from '$lib/buildingBlocks/carousel.component.svelte';
</script>

<main>
	<div class="cover">
		<Cover />
	</div>
	<h1>Solar URESquare enterprises</h1>
</main>

<style>
	main {
		height: 100vh;
		/* background-color: red; */
	}
	.cover {
		height: 450px;
		width: 100%;
		background-color: red;
		overflow: hidden;
	}
</style>
