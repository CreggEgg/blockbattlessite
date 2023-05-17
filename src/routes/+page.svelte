<script lang="ts">
	import LinkButton from "../components/LinkButton.svelte";
</script>

<main>
	<p>
		&nbsp;Welcome to Block Battles, the thrilling game that brings the
		excitement of dueling to your fingertips! Inspired by the popular <a
			target="_blank"
			href="https://www.tiktok.com/tag/blockbattles">#blockbattles</a
		> trend on TikTok, this game takes dueling to a whole new level, where strategy
		and skill are paramount.
	</p>
	<p>
		In Block Battles, you'll enter a dynamic world where players clash in
		intense duels to earn each other's decks. With a complex and deep ruleset,
		this game challenges your strategic thinking and decision-making abilities
		in real-time battles. Are you ready to showcase your mastery of tactics and
		claim victory in the arena?
	</p>
	<p>
		Prepare to immerse yourself in a diverse and ever-expanding card collection.
		Each card represents a unique character, creature, or spell, all beautifully
		crafted in a blocky aesthetic. As you progress, you'll unlock new cards,
		build powerful decks, and develop your own signature playstyle. Will you
		rely on brute force, cunning strategy, or a combination of both?
	</p>
	<p>
		To succeed in Block Battles, you must carefully construct your deck,
		selecting the perfect combination of cards that synergize with your chosen
		strategy. Craft devastating combos, unleash mighty spells, and summon
		formidable creatures to overpower your opponents. The possibilities are
		vast, and the choices you make will determine your success on the
		battlefield.
	</p>
	<p>
		Engage in exhilarating real-time duels against players from around the
		world. Utilize your deck's strengths while exploiting your opponent's
		weaknesses. With each move and countermove, you'll need to adapt your
		strategy on the fly, predicting your opponent's next move and outsmarting
		them at every turn. It's a game of wits and tactics where only the most
		skilled duelists prevail.
	</p>
	<p>
		But the thrill doesn't end with victory. When you defeat an opponent, you
		have the opportunity to claim their deck as your own, adding their cards to
		your collection. The more decks you acquire, the more diverse your
		strategies become. Experiment with different combinations, test new tactics,
		and evolve as a duelist to become unstoppable.
	</p>
	<p>
		Block Battles fosters a vibrant and passionate community of players. Connect
		with fellow duelists, share strategies, and learn from the best. Participate
		in tournaments and events that push your skills to the limit, and climb the
		ranks to prove your worth. Your name will be etched into the annals of Block
		Battles history as a legendary duelist.
	</p>
	<p>
		The game's developers are committed to delivering a rich and immersive
		experience. Regular updates introduce new cards, game modes, and features,
		ensuring that Block Battles always offers fresh challenges and surprises.
		The journey to mastery is endless, and there's always something new to
		discover.
	</p>
	<p>
		Are you ready to enter the arena and rise to the top of the <a
			target="_blank"
			href="https://www.tiktok.com/tag/blockbattles">#blockbattles</a
		>
		leaderboard? Download the game now and embrace the thrilling world of dueling.
		Prepare your deck, sharpen your mind, and get ready to outmaneuver your opponents
		in the epic battles of Block Battles. Show the world your strategic prowess and
		become the ultimate duelist!
	</p>
	<LinkButton href="/join-server" style="width: max-content;"
		>Join the server</LinkButton
	>
	<LinkButton href="/join-discord" style="width: max-content;"
		>Join the Discord</LinkButton
	>
</main>

<style>
	main {
		width: 80%;
		display: flex;
		flex-direction: column;
		padding-bottom: 5%;
		align-items: center;
		gap: 2rem;
	}

	main > p {
		font-size: 3rem;
	}
</style>
