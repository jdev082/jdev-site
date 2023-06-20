<script>
    import { page } from '$app/stores';
    import '../assets/lissom.min.css';
    import Nav from '$lib/Nav.svelte';
</script>

<style>
    h1 {
        text-align: center;
    }
</style>

<Nav />
<h1>{$page.status}: {$page.error.message}</h1>