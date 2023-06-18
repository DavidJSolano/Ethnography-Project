<script>
	import old_vught from '$lib/images/old_vught.jpg';
</script>

<svelte:head>
	<title>Camp Vught Enthography</title>
	<meta name="description" content="Camp Vught Photos" />
</svelte:head>

<section>
	<h1>
		<div class="intro">
			<picture>
				<img src={old_vught} alt="Camp Vught during WWII"/>
			</picture>
		</div>

		Camp Vught Ethnography Project<br />
	</h1>
	<h2>
		<strong>By: David Solano</strong>
	</h2>
	<a class="begin" href="/about">
		<button><strong>Begin</strong></button>
	</a>

</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
		font-family:'Courier New', Courier, monospace;
		font-weight: 1000;
		margin-bottom: 0vh;
	}

	h2 {
		font-family:'Courier New', Courier, monospace;
	}

	img {
		width: 70vw;
		height: 60vh;
		top: 0;
	}

	button {
		height: 5vh;
		width: 10vh;
		border-radius: 10px;
		font-family:'Courier New', Courier, monospace;
	}
	
	button:hover {
		background-color: lightgrey;
	}
</style>
