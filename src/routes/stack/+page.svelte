
<script>
    import { fade } from "svelte/transition";
</script>

<svelte:head>
    <title>Contact</title>
    <meta name="description" content="Information to contact me" />
</svelte:head>


    <div class="column" >
        <div class="box">
            <h1>front end</h1>
            <ul>
                <li>JavaScript</li>
                <li>Svelte</li>
                <li>SvelteKit</li>
                <li>Elixir</li>
                <li>Phoenix</li>
                <li>React</li>
                <li>React Native</li>
                <li>Next JS</li>
                <li>jQuery</li>
                <li>Apache Velocity</li>
                <li>Bootstrap</li>
                <li>Tailwind</li>
            </ul>
        </div>
        <div class="box">
            <h1>back end</h1>
            <ul>
                <li>SvelteKit</li>
                <li>Elixir</li>
                <li>Phoenix</li>
                <li>PostgreSQL</li>
                <li>GraphQL</li>
                <li>Supabase</li>
                <li>Apache Kafka</li>
            </ul>
        </div>
        <div class="box">
            <h1>tools</h1>
            <ul>
                <li>Storybook</li>
                <li>Postman</li>
                <li>Docker</li>
                <li>Git - GitHub - GitLab</li>
                <li>Angelfish Analytics</li>
                <li>Google Analytics</li>
                <li>Formstack</li>
                <li>Cascade CMS</li>
                <li>Hygraph CMS</li>
                <li>Figma</li>
                <li>Framer</li>
                <li>Miro</li>
                <li>Blender</li>
            </ul>
        </div>
        <div class="spacer"></div>
    </div>


<style>
    .contactMe {
        color: white
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
        justify-content: start;
        width: 90%;
        max-width: 1000px;
        gap: 2rem;
    }

</style>