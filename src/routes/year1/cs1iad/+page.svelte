<script lang="ts">
    import HeroTitle from '$lib/HeroTitle.svelte';
    import BackBreadcrum from '$lib/BackBreadcrum.svelte';
</script>    

<svelte:head>
    <title>Year 1 - CS1IAD | George's University Work</title>
</svelte:head>

<HeroTitle title="Year 1 - Internets Application & Database Design" subtitle="Work completed for my CS1IAD module"/>
<section class="gweb-text-layout">
    <div class="content">
        <BackBreadcrum/>
        <br>
        <p><i>Module Grade: <b>75.68%</b></i></p>
        <h2 class="gweb-link-grey"><a href="https://uniwork.georgehotten.uk/cs1iad-p1">Portfolio 1</a> <i>(23.33%)</i></h2>
        <p class="gweb-link-grey">
            For the first portfolio, I had to create a 'personal CV website'. This had to include my skills, information about me, and a way to contact me. The source code is available <a href="https://github.com/georgeataston/cs1iad-portfolio1">on GitHub</a>.
            <br><br>Grade: <b>77%</b>
        </p>

        <br>
        <h2>Portfolio 2 <i>(23.33%)</i></h2>
        <p class="gweb-link-grey">
            For the second portfolio, I had to create a normalised database to the third normal form standard. This database had to store information about clients, projects, a pool of members that can create projects, and a list of their skills.
            <br><br>Grade: <b>68%</b>
        </p>

        <br>
        <h2 class="gweb-link-grey"><a href="https://aproject.georgehotten.uk/">Portfolio 3</a> <i>(23.33%)</i></h2>
            <p class="gweb-link-grey">
                Finally for the third portfolio, I had to develop a website called 'AProject'. AProject is an software development tracker, powered by Laravel and MySQL. The source code is available <a href="https://github.com/georgeataston/cs1iad-portfolio3">on GitHub</a>.
                <br><br>Grade: <b>96%</b>
            </p>

        <br>
        <h2>Quizzes <i>(30%)</i></h2>
        <ul>
            <li>HTML, CSS and Java Script: <b>76%</b></li>
            <li>Database Design, Normalisation and Transactions: <b>50%</b></li>
            <li>Server-Side PHP: <b>68.5%</b></li>
        </ul>
        
    </div>
</section>

<style lang="scss">
    ul {
        font-size: 20px;
    }
</style>