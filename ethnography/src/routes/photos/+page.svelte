<script>
    import courtyard from '$lib/images/courtyard.jpg';
    import gaurd from '$lib/images/gaurd.jpg';
    import washroom from '$lib/images/washing.jpg';
    import clothes from '$lib/images/clothes.jpg';
    import cafeteria from '$lib/images/cafeteria.jpg';
    import beds from '$lib/images/beds.jpg';
    import memorial from '$lib/images/memorial.jpg';
    import disect from '$lib/images/disect.jpg';
    import crematory from '$lib/images/crematory.jpg';
    import ashes from '$lib/images/ashes.jpg';
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
                Gaurd towers were deployed throughout the camp to ensure that prisoners were inline
                and doing their duties.
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
                their enemies. The Weaponization of Sexual Violence podcast describes this as one of the
                stages of genocide (symbolic manifestation).
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
                At each of the seating benches, six prisoners were expected to sit. Portions of
                food were hardly enough for anyone to survive (10 oz of bread for breakfast).
            </strong>
        </p>
    </div>
    <div>
        <h1>
            Sleeping Quarters
        </h1>
        <img src={beds} alt="Sleeping Quarters"/>
        <p>
            <strong>
                The beds that the inmates slept on were made out of straw. Stacked in rows of three,
                each bed was incredibly compact. According to the museum, the barracks lacked sanitation
                and were swarmed with rats, lice, and other vermin which fostered disease.
            </strong>
        </p>
    </div>
    <div>
        <h1>
            Disection Table
        </h1>
        <img src={disect} alt="Disection table"/>
        <p>
            <strong>
                On this table, hundreds of corpses were dissected for German experiments. SS doctors
                removed organs from living people, bottled and stored them on shelves in this room.
            </strong>
        </p>
    </div>
    <div>
        <h1>
            Crematory
        </h1>
        <img src={crematory} alt="Crematory"/>
        <p>
            <strong>
                These furnaces were specially designed to burn human corpses. Large black carts
                carried these dead bodies into a furnace, where they were meant to disintegrate.
                Bones that did not burn completely were ground to powder with pestles and then dumped,
                along with the ashes.
            </strong>
        </p>
    </div>
    <div>
        <h1>
            Dumped Ashes
        </h1>
        <img src={ashes} alt="Ashes"/>
        <p>
            <strong>
                Under this gravel rectangle lies the powdery remains of cremated corpses.
                This space was once an area for dumping the ashes discussed in the previous photo.
                The star of David lies above this memorial to pay homage to the countless Jews that rest here. 
            </strong>
        </p>
    </div>
    <div>
        <h1>
            Memorial for Children
        </h1>
        <img src={memorial} alt="Memorial"/>
        <p>
            <strong>
                This memorial was created to honor all the children who passed away at Vught
                or were transferred to an extermination camp from Vught. Had this museum not existed, most of
                these victims would likely have been forgotten.
            </strong>
        </p>
    </div>
    <br/>
    <h1>Conclusion</h1>
    <p>
        <strong>
            Relating to our theme of preventing censorship within history, it's important for us to remember
            the past-- no matter how ugly it is. The Netherlands has become what it is today because its
            people recognized that genocide and discrimination toward others were wrong. The events at Vught
            relate to everything we've done in the classroom in countless ways. Genocide, human rights violations,
            and struggle all occurred at this very location. It was only with hope and determination that survivors
            of concentration camps persisted to continue living out their lives to retell their stories to the
            masses and prevent such atrocities from occurring again.
        </strong>
    </p>
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