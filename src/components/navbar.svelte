<script>
    import { page } from '$app/stores';

    let path;

    $: path = $page.url.pathname;
</script>

<nav>
    <a aria-current={$page.url.pathname === '/' ? 'page' : undefined} href="/"><i class="material-icons">home</i></a>

    <a aria-current={$page.url.pathname === '/portfolio' ? 'page' : undefined} href="/portfolio"><i class="material-icons">grid_view</i></a>

    <a aria-current={$page.url.pathname === '/contact' ? 'page' : undefined} href="/contact"><i class="material-icons">mail</i></a>
</nav>

<style>

nav {
    position: fixed;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
    bottom: 0;
    min-height: 10%;
    width: 100%;
    background: var(--transparent);
}

nav a {
    justify-self: center;
    padding: 1rem;
    height: 6em;
    width: 6em;
    text-align: center;
    border-radius: 15px;
    color: var(--black);
    text-decoration: none;
}

nav h3 {
    filter: drop-shadow(0px -2px 1px rgba(0, 0, 0, 0.25));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    text-fill-color: transparent;
    font-size: 1rem;
}
.material-icons {
    font-size: 65px;
    margin: auto;
}

@media (max-width: 1200px) {
    .column {
        width: 80% !important;
    }
}
@media (min-width: 1001px) {
    nav {
        position: fixed;
        overflow: hidden;
        display: flex;
        flex-direction: column;
        justify-content: end;
        align-items: center;
        bottom: 0;
        right: 0;
        min-height: 20%;
        max-width: 100px;
        background: var(--orange);
        margin-left: 50px;
    }
    
    nav a {
        justify-self: center;
        padding: 1rem;
        height: 6em;
        width: 6em;
        text-align: center;
        border-radius: 15px;
        color: var(--black);
        text-decoration: none;
    }
    
    }
</style>