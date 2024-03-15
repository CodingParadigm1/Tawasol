<script>

    import ContactTab from "./ContactTab.svelte";

    export let contacts = [{"name": "Tom", "age": 98},{"name": "Tom", "age": 98},{"name": "Tom", "age": 98},{"name": "Tom", "age": 98},{"name": "Tom", "age": 98},{"name": "Tom", "age": 98},{"name": "Tom", "age": 98},{"name": "Tom", "age": 98},]; 

</script>

<main>
    <section>
        {#each contacts as contact}
            <ContactTab name={contact.name} age={contact.age}/>
        {/each}
    </section>
</main>


<style>
    main{
        padding: 8px;
        padding-top:5px;
        padding-bottom:0px;
        width:100%;
        height:97%;
        display: flex;
        flex-direction: column;
        align-items: center;
        overflow: auto;
        overflow-x:hidden;
    }

    section{
        width:95%;
        height:100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        gap:5px;
    }
    @media only screen and (max-width: 600px){
        main{
            padding:4px;
        }
    }

</style>