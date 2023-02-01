<script>
	import '$lib/styles/index.scss';
</script>

<nav class="flex justify-between p-sm">
	<a href="/">Tally</a>

	<div class="flex gap-sm">
		<a href="/log-in">Log In</a>
		<a href="/sign-up">Sign Up</a>
	</div>
</nav>

<main class="flex column">
	<slot />
</main>

<style>
	main {
		--nav-height: 56px;
		min-height: calc(100vh - var(--nav-height));
		min-height: calc(100dvh - var(--nav-height));
	}
</style>
