<script lang="ts">
    import '../app.scss';
    import { page } from '$app/stores';
</script>

{#if $page.url.pathname.startsWith("/year1/")}
<nav>
    <p class="gweb-link-grey"><a href="/year1/">&lt back</a></p>
</nav>  
{:else}
<nav>
    <p class="gweb-link-grey"><a href="/">&lt home</a></p>
</nav>    
{/if}

<style lang="scss">
    p {
        font-size: 15px;
    }
</style>