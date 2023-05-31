<script lang="ts">
	import margo from '$lib/margo.jpg'
	import bullets from '$lib/bullets.jpg'
	import deer from '$lib/deer.jpg'
</script>

<svelte:head>
	<title>Lead Bullet Risks for Wildlife and Humans</title>
	<meta
		name="description"
		content="Hunters use lead ammunition to kill and wound animals. The lead fragments in their bodies and contaminates their meat and causes many effects when consumed. Human activity directly contributes to the problem by being the ones to shoot the bullets that remain in carcasses. This environmental problem isn't changing much over time, but there is more awareness now than ever due to the articles published. However, lead doesn't degrade or become less toxic over time, so the effects of lead are still being in motion."
	/>
	<meta name="og:image" content={margo} />
</svelte:head>

<div class="root">
	<nav>
		<div class="inner">
			<h1>Lead Bullet Risks for Wildlife and Humans</h1>
		</div>
	</nav>

	<main>
		<div class="inner">
			<section>
				<img src={margo} alt="Margo" />
			</section>

			<section>
				<p>
					Hunters use lead ammunition to kill and wound animals. The lead fragments in their bodies
					and contaminates their meat and causes many effects when consumed. Human activity directly
					contributes to the problem by being the ones to shoot the bullets that remain in
					carcasses. This environmental problem isn't changing much over time, but there is more
					awareness now than ever due to the articles published. However, lead doesn't degrade or
					become less toxic over time, so the effects of lead are still being in motion.
				</p>
			</section>

			<section>
				<h2>Effects</h2>
				<p>
					Lead is a toxic substance that fragments into hundreds of tiny pieces. This affects both
					wildlife and humans through consumption of the animals. Lead is poisonous and causes many
					effects, like brain damage, high blood pressure, and anemia. The long term environmental
					effects of this problem is the lead actively moving through the food chain and staying
					toxic while being in the bodies of both animals and humans. Groups of people that eat a
					lot of meat, especially ground meat, are likely more exposed to lead poisoning.
				</p>
				<img src={bullets} alt="Lead bullets" />
			</section>

			<section>
				<h2>Evidence</h2>
				<p>
					Lead is poisonous and the fragments that are shot into animals remain in their bodies. 34%
					of randomly selected packages of ground venison contained metal fragments. When fed the
					meat with lead fragments to pigs, the pigs blood levels became elevated with two days of
					ingestion. An article published in September 24, 2019 by nps.gov titled Lead Bullet Risks
					for Wildlife & Humans explains how Lead Bullets have a huge negative impact on condors and
					other wildlife.
				</p>
				<img src={deer} alt="A cute deer" />
			</section>

			<section>
				<h2>Public Awareness</h2>
				<p>
					There are many articles from national sources about this problem, which means it's a well
					known environmental problem. There is a HISTORY channel documentary about lead bullets.
					This issue deserves worldwide attention because it affects everyone, humans and animals.
					If everyone knew the effects of lead, then people would make a bigger effort to keep
					ecosystems and health safer by using non-lead bullets. People can be more aware of this
					issue if we spread the truth about why using non-lead bullets is more beneficial and then
					people would stop buying them and using them.
				</p>
			</section>

			<section>
				<h2>Solutions</h2>
				<p>
					The only solution to this issue is to stop buying and using lead bullets. Using lead
					bullets negatively impacts everyone and we should be spreading awareness about the dangers
					and harms of lead bullets.
				</p>
			</section>
		</div>
	</main>

	<footer>
		<div class="inner">
			<p class="footer-message">By Margo Mueller</p>
		</div>
	</footer>
</div>

<style lang="scss">
	.root {
		display: flex;
		flex-direction: column;
		align-items: stretch;
		height: 100%;
	}

	.inner {
		max-width: 1000px;
		width: 95%;
		margin: 0 auto;
	}

	nav,
	footer {
		flex-shrink: 0;
		padding: 1rem 0;
		background: #2f3335;
	}

	main {
		flex-grow: 1;
	}

	main .inner {
		display: flex;
		flex-direction: column;
		align-items: stretch;
		gap: 2rem;
		padding: 2rem 0;
	}

	section {
		display: flex;
		flex-direction: column;
		align-items: stretch;
		gap: 1rem;
	}

	img {
		max-width: 100%;
		max-height: 650px;
		margin: 0 auto;
		border-radius: 1rem;
	}

	.footer-message {
		text-align: center;
	}
</style>
