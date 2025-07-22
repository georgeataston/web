<script lang="ts">
    import HeroTitle from '$lib/HeroTitle.svelte';
    import BackBreadcrum from '$lib/BackBreadcrum.svelte';
</script>    

<svelte:head>
    <title>Year 2 - CS2SNS | George's University Work</title>
</svelte:head>

<HeroTitle title="Year 2 - Secure Network Services" subtitle="Work completed for my CS2SNS module"/>
<section class="gweb-text-layout">
    <div class="content">
        <BackBreadcrum/>
        <br>
        <p><i>Module Grade: <b>82.50%</b></i></p>
        <h2>Coursework <i>(50%)</i></h2>
        <p>
            This was a two-person team submission. We developed a distributed client-server application based on the UK ITV show <i>The Chase</i> using TCP/IP and a custom protocol with multiple message types. 
            We implemented SSL/TLS to secure the communication and analyzed the network traffic with Wireshark to verify encryption. 
            We also discussed additional security measures such as passkeys and dynamic firewalls.
            The report has not yet been published, it is coming soon.
            <br><br>Grade: <b>73%</b>
        </p>

        <br>
        <h2>Exam <i>(50%)</i></h2>
        <p>
            To be honest I don't really remember what was on this exam. The module covered all 7 layers of the OSI model, and the exam tested knowledge of this.
            <br><br>Grade: <b>92%</b>
        </p>
    </div>
</section>