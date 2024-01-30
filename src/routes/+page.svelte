<svelte:head>
	<title>Moxerit</title>
	<meta name="description" content="Chase's portfolio site" />
</svelte:head>


<div class="column">
    <div class="box">
        <h1 id="chase">
            CHASE ALBER
        </h1>
    </div>
    <div class="box">
        <h2 id="dev">
            FULL<br/>
            <a id="tools" href="/stack">STACK <i class="material-icons" style="font-size:60px; margin-left: 1rem;">arrow_forward</i></a>
            DEV
        </h2>
    </div>
    <!-- <div class="box row">
        <a id="tools" href="/stack">MY STACK <i class="material-icons" style="font-size:60px; margin-left: 1rem;">arrow_forward</i></a> 
    </div> -->
</div>

<style>
    #chase {
        font-size: 5rem;
        background-color: var(--black);
        font-weight: bold;
    }
    
    #dev {
        font-size: 5rem;
        background-color: var(--black);
        font-weight: bold;
    }
    #tools {
        font-size: 5rem;
        color: var(--black);
        text-decoration: none;
        font-weight: bold;
        display: flex;
        align-items: center;
        border-bottom: dotted 4px var(--black);
    }
    .hover-white:hover {
        color: var(--ivory);
    }


</style>