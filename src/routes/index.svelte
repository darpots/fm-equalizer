<script>
	import '$lib/globalStyles.css';
	import Top from '$lib/top.svelte';
	import Middle from '$lib/middle.svelte';
	import Footer from '$lib/footer.svelte';
</script>

<svelte:head>
	<title>Equalizer</title>
</svelte:head>

<main>
	<Top />
	<Middle />
	<Footer />
</main>

<!-- <Buttons icon="/icon-apple.svg" text="this is my button" /> -->
<style>
	main {
		background-image: url('/bg-main-mobile.png');
		background-position-x: 50px;
		background-position-y: -150px;
		background-repeat: no-repeat;
	}

	@media screen and (min-width: 768px) {
		main {
			background-image: url('/bg-main-tablet.png');
			background-position-x: -469px;
			background-position-y: -237px;
		}
	}

	@media screen and (min-width: 1440px) {
		main {
			background-image: url('/bg-main-desktop.png');
			background-position-x: -271px;
			background-position-y: -240px;
		}
	}
</style>
