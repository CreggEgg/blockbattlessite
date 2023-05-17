<script lang="ts">
	import "../app.css";
	let y: number = 0;
</script>

<h1 id="header">
	<img id="icon" src="./icon.png" alt="icon" />
	Block Battles
</h1>
<svelte:window bind:scrollY={y} />
<slot />

<style>
	#header {
		transition: font-size 0.2s ease-in-out 0s;

		background-color: var(--secondary);
		width: 100vw;
		text-align: center;
		margin-top: 0px;

		display: flex;
		align-items: center;
		justify-content: center;
		position: sticky;
		gap: 1rem;
		font-size: 5rem;
	}
	#icon {
		width: 4rem;
		border-radius: 0.8rem;
	}
</style>
