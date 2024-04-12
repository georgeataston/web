<script lang="ts">
    import HeroTitle from '$lib/HeroTitle.svelte';
    import BackBreadcrum from '$lib/BackBreadcrum.svelte';
</script>    

<svelte:head>
    <title>Year 1 - CS1STF | George's University Work</title>
</svelte:head>

<HeroTitle title="Year 1 - Security Thinking and Fundamentals" subtitle="Work completed for my CS1STF module"/>
<section class="gweb-text-layout">
    <div class="content">
        <BackBreadcrum/>
        <h1 class="gweb-link-grey"><a href="https://uniwork.georgehotten.uk/cs1stf/coursework.pdf">Coursework</h1>
        <p>
            The coursework assignment was to assess the vulnerabilities within a voting system. I had to identify the assets involved and how they could be at risk.
            <br><br>Grade: <b>89%</b>
        </p>

        <br>
        <h1>Exam</h1>
        <p>
            The exam was based off of knowledge about cryptography, authentication, data anonymisation and access control.
            <br><br>Grade: <b>90%</b>
        </p>
    </div>
</section>