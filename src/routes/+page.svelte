<script>
	export let data;
</script>

{#if data}
	<ul>
		{#each data.countries as country}
			<li>{country.name}</li>
		{/each}
	</ul>
{:else}
	<p>No data found</p>
{/if}
