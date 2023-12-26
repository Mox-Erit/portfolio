
<script>
    import { fade } from 'svelte/transition';
</script>

<svelte:head>
	<title>Moxerit</title>
	<meta name="description" content="Chase's portfolio site" />
</svelte:head>


<div class="column" >
    <div class="box">
        <img src="" alt="">
        <h1>welcome to my site</h1>
        <p>Hey there, my name is Chase and I develop oddities.</p>
        <h2>site theme</h2>
        <p>Frutiger Aero was a prevalent aesthetic from 2004 until around 2013. It focus on Skeuomorphism, glossy textures, and "humanism".</p>
    </div>
    <div class="box">
        <img src="" alt="">
        <h1>about me</h1>
        <p>I currently work at Montana's capital as a developer, building out applications and websites. </p>
        <h2>my stack</h2>
        <p></p>
    </div>
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