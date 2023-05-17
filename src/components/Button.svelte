<script lang="ts">
	import { createEventDispatcher } from "svelte";

	export let style: string;

	const dispatch = createEventDispatcher();
</script>

<button
	{style}
	on:click={(e) => {
		dispatch("click", e);
	}}><slot /></button
>

<style>
	button {
		background-color: var(--primary);
		border: none;
		border-radius: 5px;
		padding: 0.5rem 2rem;
		font-size: large;
		letter-spacing: 0.05rem;
		color: var(--text);
		cursor: pointer;
		transition: background-color 250ms ease-in-out 0s;
	}
	button:hover {
		background-color: var(--accent);
	}
</style>


