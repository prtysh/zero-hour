<script>
	export let segment;
</script>

<!-- <h1>{segment}</h1> -->
<nav class="navbar" role="navigation" aria-label="main navigation">
	<div class="navbar-brand">
		<a href="/" class="navbar-item">
			<img style="width:50px;height:50px" src="wbh-logo.png" alt="logo" />
		</a>
		<span class="navbar-burger" aria-label="menu" aria-expanded="false">
			<span aria-hidden="true" />
			<span aria-hidden="true" />
			<span aria-hidden="true" />
		</span>
		<div class="navbar-menu">
			<div class="navbar-start">
				<a
					href="/"
					class="navbar-item"
					class:is-active={segment === undefined}
				>
					Home
				</a>
				<a
					href="/about"
					class="navbar-item"
					class:is-active={segment === 'about'}
				>
					About
				</a>
				<a
					href="/timeline"
					class="navbar-item"
					class:is-active={segment === 'timeline'}
				>
					Timeline
				</a>
			</div>
		</div>
	</div>
</nav>

<style>
</style>
