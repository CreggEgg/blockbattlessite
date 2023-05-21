<script lang="ts">
	import "../app.css";
	import {
		Popover,
		PopoverButton,
		PopoverPanel,
	} from "@rgossiaux/svelte-headlessui";
	let infoOpen = false;
</script>

<main>
	<nav>
		<div id="ip">BLOCKBATTLES.SERV.NU</div>
		<a href="/instagram"
			><img class="nav-icon" src="/instagram.png" alt="Instagram logo" /></a
		>
		<a href="/join-discord"
			><img class="nav-icon" src="/discord.png" alt="Discord logo" /></a
		>

		<a href="/tiktok"
			><img class="nav-icon" src="/tiktok.png" alt="Tiktok logo" /></a
		>
		<a href="/youtube"
			><img class="nav-icon" src="/youtube.png" alt="Youtube logo" /></a
		>
		<span id="gap" />
		<Popover style="position: relative;">
			<PopoverButton class="infobutton"
				><div id="infoarrow">V</div>
				INFO</PopoverButton
			>

			<PopoverPanel style="position: absolute; z-index: 10;">
				<div class="panel-contents">
					<a href="/analytics">Analytics</a>
					<a href="/engagement">Engagement</a>
					<a href="/security">Security</a>
					<a href="/integrations">Integrations</a>
				</div>
			</PopoverPanel>
		</Popover>
	</nav>
	<div id="slot-div">
		<slot />
	</div>
</main>
