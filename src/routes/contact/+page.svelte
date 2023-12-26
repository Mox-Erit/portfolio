
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
            <h1>email</h1>
            <p><a class="contactMe" href="mailto:moxerit@proton.me">moxerit@proton.me</a></p>
            <h2>phone</h2>
            <p><a class="contactMe" href="tel:406-285-1366">(406) 285-1366</a></p>
        </div>
    </div>
    

<style>
    .contactMe {
        color: white
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
        justify-content: center;
        width: 90%;
        max-width: 1000px;
        gap: 2rem;
    }
    .box {
        color: #fafafa;
        background: linear-gradient(180deg, rgba(83, 85, 87, 0.9) 0%, rgba(14, 15, 15, 0.9) 100%);
        box-shadow: 0px 10px 15px rgba(0, 0, 0, 0.3), inset 0px 2px 1px rgba(255, 255, 255, 0.3), inset 0px -2px 1px rgba(0, 0, 0, 0.4);
        display: flex;
        align-items: flex-start;
        flex-direction: column;
        border-radius: 15px;
        padding: 2rem;
        width: 100%;
        gap: 5px;
    }
</style>