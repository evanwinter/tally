<script lang="ts">
	export let name: string;
	export let type: string;
</script>

<div class="my-sm">
	<label>
		{name}
		<input {type} />
	</label>
</div>

<style>
	label {
		display: block;
	}

	input {
		display: block;
		width: 100%;
	}
</style>
