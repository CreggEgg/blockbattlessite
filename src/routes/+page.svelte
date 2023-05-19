<article>
	<div id="main">
		<h1>BLOCK BATTLES</h1>
		<h2>play.thisisatemplate.net</h2>
		<div id="credits">
			<img src="blitz.png" alt="blitz" />
			<img src="spartan.png" alt="spartan" />
			<img src="cregg.png" alt="cregg" />
			<p class="name">Blitzminer</p>
			<p class="name">Spartan</p>
			<p class="name">Cregg</p>
		</div>
		<p>
			Embark on an unforgettable journey in the thrilling world of
			"BlockBattles," the captivating Minecraft minigame that draws inspiration
			from the viral TikTok trend known as #blockbattles. Engage in
			heart-pounding competitions as you strategically battle opponents,
			determined to emerge victorious. Prepare for an adrenaline-fueled
			experience as you navigate dynamic battlefields, skillfully manipulating
			blocks to gain a strategic advantage. Showcase your lightning-fast
			decision-making and cunning tactics to outsmart your foes in real-time.
			With a wealth of diverse strategies and tactics at your disposal,
			BlockBattles demands both skill and wit to claim triumph. Explore unique
			mechanics, immerse yourself in objective-driven gameplay, and seize
			valuable decks from defeated adversaries. Join the BlockBattles server now
			at the IP address above and become part of a vibrant community. Don't
			forget to follow us on social media for exciting updates, exclusive tips,
			and engaging community interactions. Are you ready to embrace the
			challenge and cement your legacy as the ultimate BlockBattles champion?
		</p>
		<div id="links">
			<a href="/join-discord" id="discord" target="_blank"
				><img class="sm-logo" src="/discord.png" alt="Discord Logo" /></a
			><a href="https://youtube.com" id="youtube" target="_blank"
				><img class="sm-logo" src="/youtube.png" alt="Youtube Logo" /></a
			><a href="https://tiktok.com" id="tiktok" target="_blank"
				><img class="sm-logo" src="/tiktok.png" alt="Tiktok Logo" /></a
			>
		</div>
	</div>
</article>

<style>
	article {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		text-align: center;
		background-image: url("/lobby.jpg");

		min-height: 100%;
		height: min-content;
		background-repeat: no-repeat;
		background-attachment: fixed;
		background-position: center;
		background-size: cover;
	}
	h1 {
		font-size: 3rem;
		margin-bottom: 0px;
	}

	h2 {
		margin-top: 0.5rem;
	}
	.name {
		color: white;
		font-weight: 700;
		font-size: 1.5rem;
		margin: 0px;
	}
	div#credits {
		width: 60%;
		display: grid;

		grid-template-rows: 1fr 1fr;
		grid-template-columns: 1fr 1fr 1fr;
		place-items: center;
		column-gap: 2rem;
	}
	div#credits > img {
		width: 5rem;
		image-rendering: pixelated;
	}

	#main {
		display: flex;
		flex-direction: column;
		align-items: center;
		width: 60%;
		height: max(90%, min-content);
		backdrop-filter: blur(10px);
		background-color: rgb(0, 0, 0, 0.65);
		border-radius: 25px;
		margin-top: 15vh;
		margin-bottom: 5vh;
	}
	p {
		font-size: 1.5em;
		width: 85%;
		font-weight: 500;
	}

	#links {
		margin-bottom: 5rem;
		margin-top: auto;
		display: flex;
		gap: 3rem;
		margin-left: 2rem;
		margin-right: 2rem;
	}
	#links > a {
		background-color: black;
		padding: 0.75rem 1.25rem;
		border-radius: 25px;
		transition: background 0.2s ease-in-out;
		scale: 1;
		transition: scale 0.2s ease-in-out;
	}

	#links > a:hover {
		scale: 1.1;
	}

	#discord {
		background: linear-gradient(0.25turn, #5865f2, black);
	}
	#youtube {
		background: linear-gradient(0.25turn, red, black);
	}
	#tiktok {
		background: linear-gradient(0.25turn, #00f2ea, black);
	}

	.sm-logo {
		width: 30%;
	}
</style>
