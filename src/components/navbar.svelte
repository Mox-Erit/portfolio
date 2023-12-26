<script>
    import { page } from '$app/stores';

    let path;

    $: path = $page.url.pathname;
</script>

<nav>
    <a aria-current={$page.url.pathname === '/' ? 'page' : undefined} href="/"><i class="material-icons" style="font-size:32px;">home</i>
       <h3>Home</h3> 
    </a>
    <div class="line"></div>
    <a aria-current={$page.url.pathname === '/portfolio' ? 'page' : undefined} href="/portfolio"><i class="material-icons" style="font-size:32px;">lightbulb</i>
       <h3>Portfolio</h3> 
    </a>
    <div class="line"></div>
    <a aria-current={$page.url.pathname === '/gallery' ? 'page' : undefined} href="/gallery"><i class="material-icons" style="font-size:32px;">dataset</i>
        <h3>Gallery</h3></a>
    <div class="line"></div>
    <a aria-current={$page.url.pathname === '/contact' ? 'page' : undefined} href="/contact"><i class="material-icons" style="font-size:32px;">mail</i>
        <h3>Contact</h3>
    </a>
</nav>

<style>
.line {
    width: 1px;
    height: 3rem;
    background: linear-gradient(180deg, rgba(255, 255, 255, 0.225) 0%, rgba(255, 255, 255, 0.18) 35.94%, rgba(255, 255, 255, 0.27) 100%);
    box-shadow: -1px 0px 1px rgba(0, 0, 0, 0.4);
}
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
    background: linear-gradient(180deg, rgba(99, 102, 104, 0.9) 0%, rgba(69, 71, 71, 0.9) 50.52%, rgba(52, 52, 52, 0.9) 53.12%, rgba(0, 0, 0, 0.9) 100%);
    box-shadow: 0px 10px 15px rgba(0, 0, 0, 0.3), inset 0px 2px 1px rgba(255, 255, 255, 0.3), inset 0px -2px 1px rgba(0, 0, 0, 0.4);
}
nav a {
    justify-self: center;
    padding: 1rem;
    height: 6em;
    width: 6em;
    text-align: center;
    border-radius: 15px;
    color: #fafafa;
    text-decoration: none;
}
/* nav a:active {
    background: linear-gradient(180deg, rgba(189, 189, 189, 0.9) 0%, rgba(128, 128, 128, 0.9) 50.52%, rgba(110, 110, 110, 0.9) 53.12%, rgba(54, 54, 54, 0.9) 100%);;
} */
nav h3 {
    filter: drop-shadow(0px -2px 1px rgba(0, 0, 0, 0.25));
    background: linear-gradient(180deg, #878C87 0%, #D3D4D3 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    text-fill-color: transparent;
    font-size: 1rem;
}
</style>