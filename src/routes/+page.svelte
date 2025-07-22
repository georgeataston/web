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
            I am a third year student at Aston University studying a bachelor's degree in Cybersecurity. I'm currently on my placement year as an IT Technian at Red Bull Racing & Technology. At the end of each academic year, I will publish all completed coursework. 
        </p>

        <h2>My Work</h2>
        <p>
            Please find the links to my currently available work.
        </p>
        <ul>
            <li class="gweb-link-grey"><a href="/year2">Year 2</a> - 75.13% (2024-25)</li>
            <li class="gweb-link-grey"><a href="/year1">Year 1</a> - 79.20% (2023-24)</li>
        </ul>
    </div>
</section>
