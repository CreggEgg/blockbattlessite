<script lang="ts">
	import { createEventDispatcher } from "svelte";

	export let style: any = undefined;
	export let href: any = undefined;
	export let about: any = undefined;

	const dispatch = createEventDispatcher();
</script>

<a {href} {about}>
	<button
		{style}
		on:click={(e) => {
			dispatch("click", e);
		}}><slot /></button
	>
</a>

<style>
	button {
		background-color: var(--primary);
		border: none;
		border-radius: 5px;
		padding: 1rem 3rem;
		font-size: large;
		letter-spacing: 0.05rem;
		color: var(--text);
		cursor: pointer;
		font-size: 3rem;
		transition: background-color 250ms ease-in-out 0s;
	}
	button:hover {
		background-color: var(--accent);
	}
</style>
