<script lang="ts">
	export let gutter: boolean = true;
</script>

<div class:px-sm={gutter}>
	<slot />
</div>

<style>
	div {
		flex: 1;
	}
</style>
