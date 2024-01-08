
<script>
    import { fade } from "svelte/transition";
</script>

<svelte:head>
    <title>Contact</title>
    <meta name="description" content="Information to contact me" />
</svelte:head>


    <div class="column" >
        <div class="box">
            <img src="" alt="">
            <h1>Frutiger Aero</h1>
            <p>Bright, hopeful, and futuristic.</p>
        </div>
        <div class="box">
            <img src="" alt="">
        </div>
        <div class="box">
            <img src="" alt="">
        </div>
        <div class="box">
            <img src="" alt="">
        </div>
        <div class="box">
            <img src="" alt="">
        </div>
        <div class="spacer"></div>
    </div>



<style>
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