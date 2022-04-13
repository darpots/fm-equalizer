<header>
	<div class="pattern">
		<img src="/src/images/bg-pattern-1.svg" alt="" />
	</div>
	<div class="logo">
		<img src="/src/images/logo.svg" alt="" />
	</div>
	<h1>We make your music sound extraordinary.</h1>
	<p>
		A system audio equalizer specifically designed for Android and iOS. Freely tune the way your
		music sounds with a professional grade parametric EQ & volume mixer. Control bass, mids, treble,
		gain control, reverb, and more!
	</p>
</header>

<style>
	header {
		width: 23.4375rem;
		padding-inline: 1.5rem;
		margin-inline: auto;
	}
	.pattern {
		display: none;
	}

	.logo {
		padding-top: 2.5rem;
		padding-bottom: 4rem;
	}

	h1 {
		font-style: normal;
		font-weight: 700;
		font-size: 2.5rem;
		line-height: 3rem;
		letter-spacing: -0.0284rem;
		color: var(--dark);
		margin-bottom: 1.25rem;
	}
	p {
		font-style: normal;
		font-weight: 400;
		font-size: 1rem;
		line-height: 1.625rem;
		color: var(--dark);
	}

	@media screen and (min-width: 48rem) {
		header {
			width: 48rem;
			padding-inline: 2.25rem;
			position: relative;
		}
		.pattern {
			overflow: hidden;
			display: block;
			position: absolute;
			right: -2.25rem;
			top: -2rem;
			width: 16.625rem;
		}
		.logo {
			padding-top: 3.875rem;
			padding-bottom: 5.9375rem;
		}
		h1 {
			font-size: 4rem;
			line-height: 4rem;
			letter-spacing: -0.0455rem;
			width: 32.5rem;
			margin-bottom: 1.75rem;
		}
		p {
			font-size: 1.125rem;
			line-height: 1.75rem;
			width: 32.125rem;
		}
	}

	@media screen and (min-width: 90rem) {
		header {
			width: 90rem;
			padding-inline: 10.3125rem;
		}
		.pattern {
			right: 0;
			width: 19.5rem;
		}
		.logo {
			padding-top: 3.875rem;
			padding-bottom: 7.9375rem;
		}
		h1 {
			font-weight: 700;
			font-size: 5.5rem;
			line-height: 5.5rem;
			letter-spacing: -0.0625rem;
			width: 63.4375rem;
			margin-bottom: 2.5rem;
		}
		p {
			font-weight: 400;
			font-size: 1.25rem;
			line-height: 2.125rem;
			width: 51.5625rem;
			margin-bottom: 20.0625rem;
		}
	}
</style>
