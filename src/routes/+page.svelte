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
		<div id="links">
			<a href="/join-discord" target="_blank">Discord</a><a
				href="https://youtube.com"
				target="_blank">Youtube</a
			><a href="https://tiktok.com" target="_blank">TikTok</a>
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
		height: 100%;
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
		height: 90%;
		background-color: rgb(0, 0, 0, 0.65);
		border-radius: 25px;
	}

	#links {
		margin-bottom: 5rem;
		margin-top: auto;
		display: flex;
		gap: 3rem;
	}
	#links > a {
	}
</style>
