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

  article{
    margin-top:10px;
    width:98%;
    height:85%;
    min-height:250px;
    background-color:grey;
    border-radius:7px;
  }
</style>
