<script>
// @ts-ignore
import {voiture} from '$lib/data/data';
</script>

<body>
    {#each voiture as car }
        <ul>
            <li>{car.marque} - {car.origin}</li>
        </ul>
    {/each}
</body>