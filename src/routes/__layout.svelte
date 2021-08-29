<script>
	import Footer from '$lib/buildingBlocks/sitemap.component.svelte';
	import Logo from '$lib/media/logo.png';
</script>

<div class="head">
	<div class="logo">
		<a href=".">
			<img alt="logo" src={Logo} />
		</a>
	</div>
	<ul>
		<li><a href="/about.page">Products</a></li>
		<li><a href="/learn-more">Projects</a></li>
		<li><a href="/learn-more">Contact Us</a></li>
		<li><a href="/legalities.page">About Us</a></li>
		<li><a href="/developingComponent">Career</a></li>
		<li><a href="/developingComponent">Component</a></li>
	</ul>
</div>
<div class="body">
	<slot />
</div>
<Footer />

<p><span>© URESquare™ 2021</span><span>®All rights reserved</span></p>

<style>
	.head {
		position: relative;
		left: 5%;
		width: 90%;
		display: flex;
		justify-content: space-between;
		align-items: center;
		z-index: 1;
		/* padding: 1rem 0; */
		height: 3rem;
		/* background-color: red; */
	}
	p {
		text-align: center;
	}
	span {
		margin: 1rem;
	}
	ul {
		margin: 0;
		padding: 0;
	}
	li {
		display: block;
		display: inline-block;
		margin-left: 1rem;
	}
	a {
		display: block;
		margin-bottom: 2px;
		background-color: none;
		text-decoration: none;
		color: #2c2c2c;
	}
	a:hover {
		margin-bottom: 0;
		border-bottom: 2px solid #2c2c2c;
	}
	.body {
		position: relative;
		width: 90%;
		height: auto;
		/* background-color: #4e4e4e; */
		left: 5%;
	}
	.logo {
		height: 100%;
		overflow: hidden;
	}
	img {
		width: auto;
		height: 3rem;
		object-fit: cover;
	}
</style>
