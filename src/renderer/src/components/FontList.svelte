<script>
	async function getFonts() {
		const res = fetch('https://api.fontsource.org/v1/fonts');
		const json = await res.json();

		console.log(json);
	}

	getFonts();
</script>

<section class="flex grow flex-col items-center p-4">
	<h2>Font list</h2>
</section>
