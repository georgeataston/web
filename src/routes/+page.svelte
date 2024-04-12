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
        <h1>Welcome!</h1>
        <p>
            I am a first year student at Aston University studying a bachelor's degree in Cybersecurity. At the end of the academic year, I will publish all completed coursework. 
        </p>

        <h2>My Work</h2>
        <p>
            Please find the links to my currently available work.
        </p>
        <ul>
            <li class="gweb-link-grey"><a href="/year1">Year 1</a> - 2023-24</li>
        </ul>
    </div>
</section>

<style lang="scss">
    ul {
        font-size: 20px;
    }
</style>
