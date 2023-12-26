<script>
    import { fade } from 'svelte/transition';
    import { page } from '$app/stores';
    import Nav from '../components/navbar.svelte'
    import './styles.css';
</script>

<svelte:head>
    <title>{$page.url.pathname.replaceAll('-', ' ')}</title>
</svelte:head>

<main in:fade>
    <div id="homepage" >    
        <section>
            <slot />   
        </section>

        <Nav />
    </div>
</main>

<style>
    section {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 2rem;
        margin-top: 1rem;
        overflow-y: auto;
    }
</style>