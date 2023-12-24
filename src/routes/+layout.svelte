<script>
    import { fade } from 'svelte/transition';
    import { page } from '$app/stores';
    import './styles.css';
</script>
<svelte:head>
    <title>{$page.url.pathname.replaceAll('-', ' ')}</title>
</svelte:head>

<main in:fade>
    <slot />
</main>
