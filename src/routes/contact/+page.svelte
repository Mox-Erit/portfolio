<div id="homepage">

    <section>
        <div class="column">
            <div class="box">
                <img src="" alt="">
                <h1>contact me</h1>
                <p>You can reach me at my email for the fastest response.</p>
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
    </section>

    <nav>
        <a href=""><i class="material-icons" style="font-size:32px;">home</i>
           <h3>Home</h3> 
        </a>
        <div class="line"></div>
        <a href=""><i class="material-icons" style="font-size:32px;">lightbulb</i>
           <h3>Portfolio</h3> 
        </a>
        <div class="line"></div>
        <a href=""><i class="material-icons" style="font-size:32px;">dataset</i>
            <h3>Gallery</h3></a>
        <div class="line"></div>
        <a href=""><i class="material-icons" style="font-size:32px;">mail</i>
            <h3>Contact</h3>
        </a>
    </nav>
</div>



<style>
    section {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 2rem;
        margin-top: 1rem;
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
        display: flex;
        flex-direction: column;
        align-items: center;
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