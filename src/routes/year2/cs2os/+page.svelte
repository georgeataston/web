<script lang="ts">
    import HeroTitle from '$lib/HeroTitle.svelte';
    import BackBreadcrum from '$lib/BackBreadcrum.svelte';
</script>    

<svelte:head>
    <title>Year 2 - CS2OS | George's University Work</title>
</svelte:head>

<HeroTitle title="Year 2 - Operating Systems" subtitle="Work completed for my CS2OS module"/>
<section class="gweb-text-layout">
    <div class="content">
        <BackBreadcrum/>
        <br>
        <p><i>Module Grade: <b>83.50%</b></i></p>
        <h2 class="gweb-link-grey"><a href="https://uniwork.georgehotten.uk/cs2os/coursework.zip">Coursework</a> <i>(25%)</i></h2>
        <p>
            This coursework assignment involved scripting in UNIX, system-level programming in C, and solving a concurrency problem using threads and synchronization. 
            It covered Bash automation, Linux system calls, and the Dining Philosophers problem.
            The link to this coursework is a zip, containing the 3 C and Bash files and a recording of them in action. This was what I submitted.
            <br><br>Grade: <b>100%</b>
        </p>

        <br>
        <h2>Exam <i>(75%)</i></h2>
        <p>
            This exam covered topics such as process management, memory management and synchronisation.
            <br><br>Grade: <b>78%</b>
        </p>
    </div>
</section>