<script>

    import ContactTab from "./ContactTab.svelte";

    export let contacts = [{"name": "Tom", "age": 98}]; 

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
        width:99%;
        height:97%;
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    section{
        padding:2px;
        width:97%;
    }

</style>