<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
	<h1>Camp Vught</h1>

	<p>
		The setting of these photos takes place in the former concentration camp, Vught. The atrocities that
		occurred in Vught during World War II are forever captured and documented by the Nationaal Monument
		Kamp Vught Museum (location of photos).
	</p>

	<p>
		Documenting historical events is crucial for human progression. When we begin to censor tragic events in human
		history, valuable lessons aren't learned and victims aren't avenged.  
	</p>
	<p class="quote">
		<strong>
			<em>
				“Those who cannot remember the past are condemned to repeat it.” 
			</em>
			<br/>
			– George Santayana
		</strong>
	</p>
	<a class="photos" href="/photos">
		<button><strong>Go to Photos!</strong></button>
	</a>
</div>
<style>
	div {
		font-family:'Courier New', Courier, monospace;
		display: flex;
		flex-direction: column;
		align-items: center;
		font-size: large;
		color: black;
	}
	.quote {
		text-align: center;
	}

	button {
		height: 7vh;
		width: 25vh;
		border-radius: 10px;
		border-width: 3px;
		font-family:'Courier New', Courier, monospace;
	}

	button:hover {
		background-color: lightgrey;
	}
</style>