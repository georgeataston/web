<script lang="ts">
    import '../app.scss';
</script>

<div class="gweb-banner"/>

<main class="gweb-container">
    <slot />
</main>

<footer class="gweb-footer footer-sticky">
    <div class="content gweb-text-layout footer-text has-text-centered">
        <p style="font-size: 15px;"><b>© George Hotten 2023</b></p>
        <p style="font-size: 15px;" class="gweb-link-white">
            <a href="https://github.com/georgeataston/web" target="_blank" rel="noopener">source</a> &middot; 
            <a href="https://george.hotten.uk" target="_blank" rel="noopener">personal site</a> &middot; 
            <a href="https://github.com/georgeataston" target="_blank" rel="noopener">github</a>
        </p>
    </div>
</footer>