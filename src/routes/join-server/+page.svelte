<script lang="ts">
	import Button from "../../components/Button.svelte";
	let ip: any;
	let text = "Copy";
</script>

<h1>Join the server at this ip!</h1>

<p
	bind:this={ip}
	style="color: var(--accent); font-size: 2rem; font-weight: 700;"
>
	google.com
</p>
<Button
	style="padding: 1rem 3rem;
font-size: large; background-color: var(--secondary); cursor: {text == 'Copied'
		? 'auto'
		: 'pointer'}"
	on:click={() => {
		navigator.clipboard.writeText(ip.innerText);
		text = "Copied";
	}}>{text}</Button
>
