<script>
    import Nav from "../lib/components/nav.svelte";

</script>

<header>
    <Nav />
</header>

<article>
    <slot></slot>
</article>

<style>
    header {
        position: sticky;
        top: 5px;
    }
</style>