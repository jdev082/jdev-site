<script>
    import '../assets/lissom.min.css';
    import Nav from '$lib/Nav.svelte';
    import { concurrent } from 'svelte-typewriter/modes';
    const code = "alert('Hello, World!')";
</script>

<style>
body {
    text-align: center;
}
</style>

<Nav />
<body>
    <h1 use:concurrent={{ interval: 150 }}>Hello, World!</h1>
    <p use:concurrent={{ interval: 50 }}>I am jdev082, and this is my website!</p>
</body>