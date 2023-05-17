<script lang="ts">
	import Button from "../components/Button.svelte";

	let y: number;
</script>

<h1
	id="header"
	style="font-size: {y < 50 ? '5rem' : '2rem'}; position: {y < 50
		? 'relative'
		: 'sticky'};"
>
	<img id="icon" src="./icon.png" alt="icon" />
	Block Battles
</h1>
<main>
	<p>
		&nbsp;Welcome to Block Battles, the ultimate gaming experience that has
		taken the world by storm! Inspired by the popular <a
			target="_blank"
			href="https://www.tiktok.com/tag/blockbattles">#blockbattles</a
		> trend on TikTok, this thrilling game will test your strategic skills, reflexes,
		and creativity in a fast-paced virtual battlefield.
	</p>
	<p>
		In Block Battles, you will find yourself immersed in a vibrant world of
		blocks where you can build, defend, and conquer. Gather your friends or
		challenge players from around the globe as you compete in intense battles
		filled with explosive action. Are you ready to showcase your skills and
		become the champion of Block Battles?
	</p>
	<p>
		Create your own unique character and customize it with a wide range of
		blocky accessories, stylish outfits, and powerful weapons. With countless
		customization options available, you can truly make your character stand out
		and reflect your personality. From armored knights to futuristic cyborgs,
		the choice is yours!
	</p>
	<p>
		Once you've assembled your dream character, it's time to step onto the
		battlefield. Engage in thrilling team-based matches where cooperation and
		strategy are key to victory. Use the environment to your advantage,
		construct defensive structures, and strategically position yourself to
		outsmart your opponents.
	</p>
	<p>
		Block Battles offers a variety of game modes to keep you entertained for
		hours on end. Test your aim and reflexes in intense shooting battles,
		compete for control of valuable resources in capture-the-flag mode, or
		engage in epic team deathmatches where every second counts. The
		possibilities are endless, and the battles are always intense.
	</p>
	<p>
		As you progress through the game, you'll earn experience points, unlock new
		weapons, and discover powerful abilities that will give you an edge on the
		battlefield. Adapt your playstyle, experiment with different strategies, and
		rise through the ranks to become the ultimate Block Battles champion.
	</p>
	<p>
		Join the global community of Block Battles players and connect with
		like-minded gamers from all walks of life. Share your epic moments, learn
		from the best, and participate in exciting tournaments and events that will
		put your skills to the test. Are you ready to make your mark on the <a
			target="_blank"
			href="https://www.tiktok.com/tag/blockbattles">#blockbattles</a
		>
		leaderboard?
	</p>
	<p>
		Whether you're a casual gamer or a hardcore competitor, Block Battles offers
		endless fun, excitement, and intense battles that will keep you coming back
		for more. Download the game now and prepare to embark on a blocky adventure
		like no other. Get ready to build, fight, and conquer in the world of Block
		Battles!
	</p>
	<Button style="width: min-content">Join</Button>
</main>

<svelte:window bind:scrollY={y} />

<style>
	#header {
		transition: font-size 0.2s ease-in-out 0s;

		top: 0px;
		background-color: var(--secondary);
		width: 100%;
		text-align: center;
		margin-top: 0px;
		height: 6rem;
		display: flex;
		align-items: center;
		justify-content: center;
		gap: 1rem;
	}
	#icon {
		width: 4rem;
		border-radius: 0.8rem;
	}
	main {
		width: 80%;
		display: flex;
		flex-direction: column;
		padding-bottom: 5%;
		align-items: center;
	}

	main > p {
		font-size: 4rem;
	}
</style>
