
<script>
    import { fade } from "svelte/transition";
</script>

<svelte:head>
    <title>Contact</title>
    <meta name="description" content="Information to contact me" />
</svelte:head>


    <div class="column" >
        <div class="box">   
            <h1>gallery</h1>
            <br/>
            <p>My favorite media I take inspiration from for my work.</p>
        </div>
        <div class="box">
            <img src="" alt="">
            <a href="/gallery/frutiger-aero">Frutiger Aero</a>
        </div>
        <div class="box">
            <img src="" alt="">
            <a href="/gallery/frutiger-metro">Frutiger Metro</a>
        </div>
        <div class="box">
            <img src="" alt="">
            <a href="/gallery/dieter-rams">Dieter Rams</a>
        </div>
        <div class="box">
            <img src="" alt="">
            <a href="/gallery/donald-deskey">Donald Deskey</a>
        </div>
        <div class="box">
            <img src="" alt="">
            <a href="/gallery/peter-muller">Peter Muller</a>
        </div>
        <div class="spacer"></div>
    </div>


<style>
    a {
        color: white;
        font-size: 1.2em;
    }
    h1 {
        font-size: 2.4rem;
        filter: drop-shadow(0px -2px 1px rgba(0, 0, 0, 0.25));
        background: linear-gradient(180deg, #878C87 0%, #D3D4D3 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        background-clip: text;
        text-fill-color: transparent;
        line-height: 125%;
        margin: 0 0 5px;
    }
    h2 {
        font-size: 2.4rem;
        filter: drop-shadow(0px -2px 1px rgba(0, 0, 0, 0.25));
        background: linear-gradient(180deg, #878C87 0%, #D3D4D3 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        background-clip: text;
        text-fill-color: transparent;
        line-height: 125%;
        margin: 0 0 5px;
    }
    p {
        font-size: 1.2rem;
    }
    .line {
        width: 1px;
        height: 36px;
        background: linear-gradient(180deg, rgba(255, 255, 255, 0.225) 0%, rgba(255, 255, 255, 0.18) 35.94%, rgba(255, 255, 255, 0.27) 100%);
        box-shadow: -1px 0px 1px rgba(0, 0, 0, 0.4);
    }
    .column {
        height: 100vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: start;
        width: 90%;
        max-width: 1000px;
        gap: 2rem;
    }
</style>