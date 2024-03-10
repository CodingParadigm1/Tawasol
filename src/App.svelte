<script>
  import Menu from './lib/Menu.svelte'
  import Contacts from './lib/Contacts.svelte';
</script>

<main>
  <Menu />
  <article>
    <Contacts/>
  </article>
</main>


<style>
  main{
    background-color:white;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: start;
    height:100%;
  }
</style>
