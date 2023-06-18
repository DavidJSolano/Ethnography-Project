<script>
    import courtyard from '$lib/images/courtyard.jpg';
    import gaurd from '$lib/images/gaurd.jpg';
    import washroom from '$lib/images/washing.jpg';
    import clothes from '$lib/images/clothes.jpg';
    import cafeteria from '$lib/images/cafeteria.jpg';
    
</script>

<svelte:head>
    <title>Photos</title>
	<meta name="description" content="Photos for this project" />
</svelte:head>
<div>
    <h1>
        <strong>
            Photos
        </strong>
    </h1>
    <div>
        <h1>
            Camp Vught Replica
        </h1>
        <img src={courtyard} alt="Courtyard"/>
        <p>
            <strong>
                At the entrance of the lawn lies a replica of the entire camp. 
                This model lies on top of a platform where prisoners would have roll calls.
                The prisoners would often be forced to bear through extreme weather conditions with
                just the thin clothes that they were provided. 
            </strong>
        </p>
    </div>
    <div>
        <h1>
            Gaurd Tower
        </h1>
        <img src={gaurd} alt="Courtyard"/>
        <p>
            <strong>
                Gaurd towers were deployed throughout the camp to ensure that prisoners were inline.
            </strong>
        </p>
    </div>
    <div>
        <h1>
            Washroom
        </h1>
        <img src={washroom} alt="Wash room"/>
        <p>
            <strong>
                Entering one of the housing quarters, there is a washroom for prisoners to clean
                their clothes and do laundry.
            </strong>
        </p>
    </div>
    <div>
        <h1>
            Camp Clothes
        </h1>
        <img src={clothes} alt="Clothes"/>
        <p>
            <strong>
                These are the clothes that all prisoners were required to wear at all times. By forcing
                prisoners to wear such bland-looking apparel, the Nazis were effectively dehumanizing
                their enemies.
            </strong>
        </p>
    </div>
    <div>
        <h1>
            Cafeteria
        </h1>
        <img src={cafeteria} alt="Cafeteria"/>
        <p>
            <strong>
                The cafeteria was just barely large enough to fit all of the prisoners.
                At each of the seating benches, 6 prisoners were expected to sit. Portions of
                food were hardly enough for anyone to survive (10 oz of bread for breakfast).
            </strong>
        </p>
    </div>
    <div>
        <h1>
            Gaurd Tower
        </h1>
        <img src={gaurd} alt="Courtyard"/>
        <p>
            <strong>
                Gaurd towers were deployed throughout the camp to ensure that prisoners were inline.
            </strong>
        </p>
    </div>
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
    img {
		width: 40vw;
		height: 70vh;
		top: 0;
	}
</style>