<script>
  import Menu from './lib/Menu.svelte'
  import Contacts from './lib/Contacts.svelte';
    import Settings from './lib/Settings.svelte';

  let pages = [Contacts, Settings]; 
  let current_page = 0; 
</script>

<main>  
  <Menu bind:counter = {current_page}/>
  <article>
      <svelte:component this={pages[current_page]}/>
  </article>
</main>


<style>
  main{
    background-color:white;
    display: flex;
    flex-direction: column;
    align-items: center;
    height:100%;
  }

  article{
    margin-top:10px;
    width:98%;
    height:85%;
    min-height:250px;
    background-color:grey;
    border-radius:7px;
    overflow: hidden;
  }
</style>
