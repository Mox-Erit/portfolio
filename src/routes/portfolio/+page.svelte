<svelte:head>
    <title>Contact</title>
    <meta name="description" content="Information to contact me" />
</svelte:head>


    <div class="column" >
        <div class="box">
            <h1>PORTFOLIO</h1>  
        </div>
        <div class="box border">  
                <a href="https://liv.mt.gov/Brands-Enforcement/Find-a-brand-inspector"><h2>LIVESTOCK SEARCH</h2>
                <p>Searchable database for brand inspectors under the Department of Livestock within Montana.</p>
            </a> 
        </div>
        <div class="box border">             
                <a href="https://dnrc.mt.gov/"><h2>DNRC REDESIGN</h2>
                <p>Redesigned the DNRC website from the ground-up. Trained over 200+ DNRC employees, contributors, and developers to use the Cascade CMS.</p>
            </a> 
        </div>
        <div class="box border">
                <a href="https://mt.gov/"><h2>MT.GOV REBUILD</h2>
                <p>Under the Governor's orders - coordinated the renewal of mt.gov to resolve broken applications, accessibility issues, and mobile responsiveness. Migrated entire site from GitLab to CascadeCMS, converting .NET code to our stack.</p>
            </a> 
        </div>
        <div class="box border">         
            <a href="https://lmi.delaware.gov/"><h2>DELAWARE LMI</h2>
            <p>Migrated the State of Delaware's Labor Market Index website to our Cascade CMS. Brought site to 508 accessibility compliance, faster data graphs, and mobile responsiveness.</p>
        </a> 
    </div>
        <div class="spacer"></div>
    </div>


<style>
    .box:hover {
        background-color: #ff7f5c;
    }
    h1 {
        background-color: var(--black);
        font-weight: bold;
        font-size: 4rem;
    }
    h2 {
        background-color: var(--black);
        font-weight: bold;
        font-size: 3rem;
    }
    p {
        font-size: 2rem;

        color: var(--black);
    }
    @media (min-width: 1001px) {
        p {
        font-size: 4rem;

        color: var(--black);
        }
    }
    a {
        font-size: 4rem;
        text-decoration: none;
        margin: 0 auto;
    }
    ul {
        margin-left: 2rem;
    }
    li{
        color: var(--black);
        font-size: 2rem;
        font-weight: bold;
    }
    .border {
        border: solid 4px var(--black);
    }
@media (min-width: 1001px) {
    h2 {
        background-color: var(--black);
        font-weight: bold;
        font-size: 4rem;
    }
}
</style>