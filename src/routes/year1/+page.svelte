<script lang="ts">
    import HeroTitle from '$lib/HeroTitle.svelte';
    import BackBreadcrum from '$lib/BackBreadcrum.svelte';
</script>    

<svelte:head>
    <title>Year 1 | George's University Work</title>
</svelte:head>

<HeroTitle title="Year 1" subtitle="Work completed in my first year at university"/>
<section class="gweb-text-layout">
    <div class="content">
        <BackBreadcrum/>
        <h1>Uploadable Work</h1>
        <p>Not all modules have work I can upload for them (i.e., purely assessed on quizzes and exams). However, the following modules do.</p>
        <h2 class="gweb-link-grey"><a href="/year1/cs1oop">CS1OOP - Object Oriented Programming</a></h2>
        <p>
            Assessment:
        </p>
        <ul>
            <li>Written Exam - 50%</li>
            <li>TP1 Quizzes - 25%</li>
            <li>TP2 Labs - 15%</li>
            <li>TP2 JavaFX Lab - 10%</li>
        </ul>
        <p>Final Grade: <b>90.39%</b></p>

        <br>
        <h2 class="gweb-link-grey"><a href="/year1/cs1stf">CS1STF - Security Thinking and Fundamentals</a></h2>
        <p>
            Assessment:
        </p>
        <ul>
            <li>Online Exam - 50%</li>
            <li>Coursework - 50%</li>
        </ul>
        <p>Final Grade: <b>89.50%</b></p>

        <br>
        <h2 class="gweb-link-grey"><a href="/year1/cs1psa">CS1PSA - Professional and Social Aspects of Computing</a></h2>
        <p>
            Assessment:
        </p>
        <ul>
            <li>Group Coursework - 60%</li>
            <li>Individual Presentation - 40%</li>
        </ul>
        <p>Final Grade: <b>66.20%</b></p>

        <br>
        <h2 class="gweb-link-grey"><a href="/year1/cs1iad">CS1IAD - Internet Applications & Database Design</a></h2>
        <p>
            Assessment:
        </p>
        <ul>
            <li>Portfolios - 70%</li>
            <li>Online Quizzes - 30%</li>
        </ul>
        <p>Final Grade: <b>75.68%</b></p>

        <br>
        <h1>Other Modules</h1>
        <p>These modules not do have any work associated with them.</p>

        <h2>CS1CS - Computer Systems</h2>
        <p>
            Assessment:
        </p>
        <ul>
            <li>Online Quizzes - 80%</li>
            <li>Linux Lab Quizzes - 20%</li>
        </ul>
        <p>Final Grade: <b>78.35%</b></p>

        <br>
        <h2>CS1MCP - Mathmatics for Computing Professionals</h2>
        <p>
            Assessment:
        </p>
        <ul>
            <li>Online Quizzes - 50%</li>
            <li>Written Exam - 50%</li>
        </ul>
        <p>Final Grade: <b>67.38%</b></p>
    </div>
</section>


<style lang="scss">
    ul {
        font-size: 20px;
    }
</style>