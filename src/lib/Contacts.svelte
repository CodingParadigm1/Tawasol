<script>

    import ContactTab from "./ContactTab.svelte";

    export let contacts = []; 

</script>

<main>
    <section>
        {#each contacts as contact}
            <ContactTab name={contact.name} age={contact.age}/>
        {/each}
    </section>
</main>