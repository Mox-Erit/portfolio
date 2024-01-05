
<script>
    import { fade } from 'svelte/transition';
</script>

<svelte:head>
	<title>Moxerit</title>
	<meta name="description" content="Chase's portfolio site" />
</svelte:head>


<div class="column">
    <div class="box">
        <img src="" alt="">
        <h1>welcome to my site (WIP IT IS UGLY)</h1>
        <p>Hey there, my name is Chase and I develop oddities like this "old" looking site from the 2000s.</p>
        <br />
        <h2>site theme</h2>
        <p>This theme, Frutiger Aero, was a prevalent aesthetic from 2004 until around 2013. It focuses on Skeuomorphism, glossy textures, and "humanism". </p>
        <br/>
        <p>Feel free to change the site's theme below:</p>
        <br/>
        <select name="theme" id="themeSelect">
            <option value="Frutiger Aero">Frutiger Aero</option>
            <option value="Frutiger Metro">Frutiger Metro</option>
            <option value="Dieter Rams">Dieter Rams</option>
        </select>
    </div>
    <div class="box">
        <img src="" alt="">
        <h1>about me</h1>
        <p>Currently I work with my state's government as a software engineer - building out applications and websites for our citizens or neighboring states. In my freetime I can be found licking collectible stamps or slinging flies on the the Missouri river. </p>
        <br />
        <h2>my stack</h2>
        <a class="stack" href="/stack">Click here to see what I use.</a>
    </div>
    <div class="spacer">

    </div>
</div>

<style>
    .stack {
        color: white;
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