<script lang="ts">
	import { Input, Page } from '$lib/components';

	function handleSubmit() {
		console.log('submit');
	}
</script>

<Page>
	<h1>Log In</h1>

	<form on:submit={handleSubmit}>
		<Input name="Email" type="email" />
		<Input name="Password" type="password" />

		<button type="submit">Log In</button>
	</form>
</Page>
