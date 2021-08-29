<script>
	let sitemap;
</script>

<main>
	<div class="base">
		<h1>Site Map</h1>
		<div class="columns">
			<div class="column">
				<h3>C1</h3>
				<ul>
					<li>Link 1</li>
					<li>Link 2</li>
					<li>Link 3</li>
				</ul>
			</div>
			<div class="column">
				<h3>C2</h3>
				<ul>
					<li>Link 1</li>
					<li>Link 2</li>
					<li>Link 3</li>
				</ul>
			</div>
			<div class="column">
				<h3>C3</h3>
				<ul>
					<li>Link 1</li>
					<li>Link 2</li>
					<li>Link 3</li>
				</ul>
			</div>
		</div>
	</div>
</main>

<style>
	main {
		background-color: #2c2c2c;
		color: white;
		display: block;
		position: relative;
		width: 90%;
		left: 5%;
	}
	ul {
		list-style-type: none;
	}
	li {
		margin: 1rem 0;
	}
	.columns {
		display: flex;
		align-items: center;
		justify-content: space-around;
	}
	.column {
		/* background-color: burlywood; */
		width: 250px;
	}
</style>
