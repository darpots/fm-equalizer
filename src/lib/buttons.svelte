<script>
	export let icon = '';
	export let text = '';
	export let type = 'primary';
</script>

<button class={type}>
	<img src={icon} alt="" />
	{text}
</button>

<style>
	button {
		font-weight: 700;
		font-size: 18px;
		padding-block: 15px;
		border-radius: 12px;
		letter-spacing: -0.18px;
		border: 0;
		transition: all 0.2s ease-in-out;
		display: flex;
		justify-content: center;
		align-items: center;
		width: 100%;
	}

	.primary {
		background-color: var(--dark);
		color: var(--light);
	}

	.primary:hover {
		background-color: var(--aqua);
		color: var(--light);
	}

	.secondary {
		background-color: var(--light);
		color: var(--dark);
	}

	.secondary:hover {
		background-color: var(--lightOrange);
		color: var(--dark);
	}

	img {
		margin-right: 8px;
	}
</style>
