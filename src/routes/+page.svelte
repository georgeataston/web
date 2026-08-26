<script lang="ts">
    import HeroTitle from '$lib/HeroTitle.svelte';
    import BackBreadcrum from '$lib/BackBreadcrum.svelte';
</script>    

<svelte:head>
    <title>George's University Work</title>
</svelte:head>

<HeroTitle title="George's University Work" subtitle="My university coursework and programming projects"/>
<section class="gweb-text-layout">
    <div class="content">
        <p>
            I am a final year student at Aston University studying a bachelor's degree in Cybersecurity. In August 2026, I finished my placement year as an IT Technician at Red Bull Racing & Technology. At the end of each academic year, I will publish all completed coursework. 
        </p>

        <h2>My Work</h2>
        <p>
            Please find the links to my currently available work.
        </p>
        <ul>
            <li class="gweb-link-grey">Placement Year - 69.00% (2025-26)</li>
            <li class="gweb-link-grey"><a href="/year2">Year 2</a> - 75.13% (2024-25)</li>
            <li class="gweb-link-grey"><a href="/year1">Year 1</a> - 79.20% (2023-24)</li>
        </ul>
    </div>
</section>
