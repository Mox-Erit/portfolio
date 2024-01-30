
<script>
    import { fade } from 'svelte/transition';
</script>

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
            STACK<br/>
            DEV
        </h2>
    </div>
    <div class="box row">
        <a id="tools" href="/stack">MY STACK</a> <i class="material-icons" style="font-size:60px; margin-left: 1rem;">arrow_forward</i>
    </div>
</div>

<style>
    #chase {
        font-size: 5rem;
        background-color: #000000;
        font-weight: bold;
    }
    #dev {
        font-size: 5rem;
        background-color: #000000;
        font-weight: bold;
    }
    #tools {
        font-size: 3rem;
        color: #000000;
        text-decoration: none;
        font-weight: bold;
    }
    .row {
        flex-direction: row;
        align-items: center;
    }

</style>