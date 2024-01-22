
<script>
    import { fade } from "svelte/transition";
</script>

<svelte:head>
    <title>Contact</title>
    <meta name="description" content="Information to contact me" />
</svelte:head>


    <div class="column" >
        <div class="box">
            <h1>portfolio</h1>  
            <p>Projects I completed from my job, private commissions, or personal works.</p>
        </div>
        <div class="box">
 
                <h1>Livestock search</h1>
                <a href="https://liv.mt.gov/Brands-Enforcement/Find-a-brand-inspector">
                    <img src="img/deptLivestock.png" alt="">
                </a> 
                <br/>
                <p>Searchable database to find brand inspectors for the Department of Livestock within Montana.</p>
                <br/>
                <ul>
                    <li>Cascade CMS</li>
                    <li>Apache Velocity</li>
                    <li>DataTables jQuery</li>
                    <li>Bootstrap 5</li>
                </ul>

        </div>
        <div class="box">
                <h1>DNRC website</h1>
                <a href="https://dnrc.mt.gov/">
                    <img src="img/dnrcLogo.png" alt="">
                </a> 
                <br/>
                <p>Redesigned the DNRC website from the ground-up. Trained over 200+ DNRC employees, contributors, and developers to use the Cascade CMS.</p>
                <br/>
                <ul style="margin-left: 15px;">
                    <li>Cascade CMS</li>
                    <li>Apache Velocity</li>
                    <li>DataTables jQuery</li>
                    <li>Bootstrap 5</li>
                    <li>Figma</li>
                    <li>Formstack</li>
                </ul>
        </div>
        <div class="box">
                <h1>mt.gov rebuild</h1>
                <a href="https://mt.gov/">
                    <img src="img/mtSeal.png" alt="">
                </a> 
                <br/>
                <p>Under Governor orders - coordinated the renewal of mt.gov to resolve broken applications, accessibility issues, and mobile responsiveness. Migrated entire site from GitLab to CascadeCMS, converting .NET code to our stack.</p>
                <br/>
                <ul>
                    <li>weather.gov API</li>
                    <li>Cascade CMS</li>
                    <li>Apache Velocity</li>
                    <li>jQuery</li>
                    <li>Bootstrap 5</li>
                    <li>Figma</li>
                    <li>Formstack</li>
                </ul>
        </div>
        <div class="box">
            <h1>Delaware LMI</h1>
            <a href="https://lmi.delaware.gov/">
                <img style="width: 100%; height: auto;" src="img/delawareLMI.png" alt="">
            </a> 
            <br/>
            <p>Migrated the State of Delaware's Labor Market Index website to our Cascade CMS. Brought site to 508 accessibility compliance, faster data graphs, and mobile responsiveness.</p>
            <br/>
            <ul>
                <li>Tableau</li>
                <li>ReadSpeaker</li>
                <li>React</li>
                <li>Cascade CMS</li>
                <li>Apache Velocity</li>
                <li>DataTables jQuery</li>
                <li>jQuery</li>
                <li>Bootstrap 5</li>
                <li>Formstack</li>
            </ul>
    </div>
        <div class="spacer"></div>
    </div>


<style>
    img {
        display: flex;
        width: auto;
        height: 180px;
        
    }
    a {
        text-decoration: none;
        margin: 0 auto;
    }
    ul {
        margin-left: 15px;
    }
    p {
        font-size: 1.6rem;
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