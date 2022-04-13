<script>
	import Buttons from './buttons.svelte';
</script>

<section>
	<div class="pattern">
		<img src="/src/images/bg-pattern-2.svg" alt="" />
	</div>
	<div class="illustration">
		<img src="/src/images/illustration-app.png" alt="" />
	</div>
	<div class="cta">
		<h1>Premium EQ</h1>
		<p class="text">
			Get expert-level control with a robust equalizer, volume mixer, and spatial audio. Take your
			listening experience to a whole new level and access all our incredible features!
		</p>
		<p class="price"><span>$4</span>/ month</p>
		<div style="margin-bottom: 20px;">
			<Buttons icon="/src/images/icon-apple.svg" text="iOS Download" />
		</div>
		<Buttons icon="/src/images/icon-android.svg" text="Android Download" type="secondary" />
	</div>
</section>

<style>
	section {
		background-color: var(--dark);
		height: 37.5rem;
		margin-inline: auto;
		border-radius: 0.75rem;
		width: 23.4375rem;
		position: relative;
		margin-top: 10.375rem;
		margin-bottom: 24.125rem;
	}
	.pattern {
		position: absolute;
		margin: 0 auto;
		width: 17.5rem;
		left: 0;
		right: 0;
	}
	.illustration {
		width: 13.0625rem;
		position: relative;
		margin-inline: auto;
		top: -5.5rem;
	}

	.cta {
		background-color: var(--deepOrange);
		padding: 3rem 2rem;
		border-radius: 0.75rem;
		position: relative;
		top: -3rem;
	}

	h1 {
		font-weight: 700;
		font-size: 2rem;
		line-height: 2.5rem;
		color: var(--light);
		margin-bottom: 0.75rem;
	}
	p {
		font-style: normal;
		font-weight: 400;
		font-size: 1.125rem;
		line-height: 1.75rem;
		color: var(--light);
	}
	.text {
		margin-bottom: 2.25rem;
	}

	.price {
		margin-bottom: 2rem;
		display: flex;
		align-items: center;
	}

	.price span {
		font-weight: 700;
		font-size: 4.0625rem;
		line-height: 3.25rem;
		margin-right: 1rem;
	}
	@media screen and (min-width: 48rem) {
		section {
			width: 43.5rem;
			margin-bottom: 13.75rem;
		}
		.illustration {
			margin: 0;
			left: 3rem;
			width: 16.875rem;
		}
		.cta {
			width: 24.9375rem;
			top: -22.5rem;
			left: 13.75rem;
			padding: 3rem;
		}
	}

	@media screen and (min-width: 90rem) {
		section {
			width: 69.375rem;
			margin-bottom: 12.1875rem;
		}
		h1 {
			font-size: 2.5rem;
			line-height: 3.25rem;
		}
		p {
			width: 20.8125rem;
			font-size: 1.25rem;
			line-height: 2.125rem;
		}
		.cta {
			width: 27.875rem;
			padding: 3.625rem 3.375rem 3rem 3.375rem;
			left: 35.5625rem;
			top: -28.75rem;
		}
		.pattern {
			margin: 0;
			left: 21rem;
			top: -1.25rem;
		}
		.illustration {
			top: -12.5rem;
			left: 8rem;
			width: 17.5rem;
		}
	}
</style>
