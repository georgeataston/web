<script lang="ts">
    import '../gweb.scss';
    import { page } from '$app/stores';
</script>


{#if $page.url.pathname.startsWith("/year1/")}
    <nav>
        <p class="gweb-link-grey"><a href="/year1/">&lt back</a></p>
    </nav>  
{:else if $page.url.pathname.startsWith("/year2/")}
    <nav>
        <p class="gweb-link-grey"><a href="/year2/">&lt back</a></p>
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