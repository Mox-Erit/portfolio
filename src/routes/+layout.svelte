<script>
    import { fade } from 'svelte/transition';
    import { page } from '$app/stores';
    import Nav from '../components/navbar.svelte'
    import './styles.css';
</script>

<svelte:head>

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
        height: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 2rem;
        overflow-y: auto;
    }
</style>