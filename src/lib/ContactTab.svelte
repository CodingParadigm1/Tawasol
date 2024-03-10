<script>
    export let age = 0, name=""; 
</script>

<main>
    <section id="profile-image">
        <img src="" alt="contact img">
    </section>
    <section id="options">
        {#if age>0}
            <span class="age">
                {age}
            </span>
        {/if}
        <span id="name">
            {name}
        </span>
    </section>
</main>

<style>
    *{
        color:black;
    }
    main{
        padding:5px;
        background-color: grey;
        width:98%;
        height:40px;
        display: flex;
        align-items: center;
        justify-content: space-between;
        border-radius:7px;
    }
    section#options{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
</style>