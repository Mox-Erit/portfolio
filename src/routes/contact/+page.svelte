
<script>
    import { fade } from "svelte/transition";
</script>

<svelte:head>
    <title>Contact</title>
    <meta name="description" content="Information to contact me" />
</svelte:head>
    <div class="column" >
        <div class="box">
            <br/>
            <br/>
            <br/>
            <br/>
            <br/>
            <br/>
            <br/>
            <h1>EMAIL</h1>
            <p><a class="contactMe" href="mailto:moxerit@proton.me">moxerit@proton.me</a></p>
            <br/>
            <br/>
            <br/>
            <h2>PHONE</h2>
            <p><a class="contactMe" href="tel:406-285-1366">(406) 285-1366</a></p>
        </div>
    </div>
    

<style>
    .contactMe {
        color: white
    }
    h1 {
        font-size: 5rem;
        background-color: #000000;
        font-weight: bold;
    }
    h2 {
        font-size: 5rem;
        background-color: #000000;
        font-weight: bold;
    }
    p {
        font-size: 3rem;;
    }
    .contactMe {
        color: #000000;
    }
</style>