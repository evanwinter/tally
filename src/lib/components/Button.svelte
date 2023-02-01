<script lang="ts">
	export let disabled: boolean | undefined = false;
	export let onClick: () => void;
</script>

<button class="border rounded-sm py-sm px-md" on:click={onClick} {disabled}>
	<slot />
</button>
