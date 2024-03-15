<script>
  export let counter = 0; 
</script>

<main>
  <h3>
    Tawasol
  </h3>
  <section id="options">
    <section class="icon" on:click={counter=0}>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 -85 640 712">
        <path d="M208 352c114.9 0 208-78.8 208-176S322.9 0 208 0S0 78.8 0 176c0 38.6 14.7 74.3 39.6 103.4c-3.5 9.4-8.7 17.7-14.2 24.7c-4.8 6.2-9.7 11-13.3 14.3c-1.8 1.6-3.3 2.9-4.3 3.7c-.5 .4-.9 .7-1.1 .8l-.2 .2 0 0 0 0C1 327.2-1.4 334.4 .8 340.9S9.1 352 16 352c21.8 0 43.8-5.6 62.1-12.5c9.2-3.5 17.8-7.4 25.3-11.4C134.1 343.3 169.8 352 208 352zM448 176c0 112.3-99.1 196.9-216.5 207C255.8 457.4 336.4 512 432 512c38.2 0 73.9-8.7 104.7-23.9c7.5 4 16 7.9 25.2 11.4c18.3 6.9 40.3 12.5 62.1 12.5c6.9 0 13.1-4.5 15.2-11.1c2.1-6.6-.2-13.8-5.8-17.9l0 0 0 0-.2-.2c-.2-.2-.6-.4-1.1-.8c-1-.8-2.5-2-4.3-3.7c-3.6-3.3-8.5-8.1-13.3-14.3c-5.5-7-10.7-15.4-14.2-24.7c24.9-29 39.6-64.7 39.6-103.4c0-92.8-84.9-168.9-192.6-175.5c.4 5.1 .6 10.3 .6 15.5z"/>
      </svg>
    </section>
    <section class="icon" on:click={counter=1}>
      <svg  xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="35" height="35" viewBox="0 0 40 50">
        <path d="M 5 8 A 2.0002 2.0002 0 1 0 5 12 L 45 12 A 2.0002 2.0002 0 1 0 45 8 L 5 8 z M 5 23 A 2.0002 2.0002 0 1 0 5 27 L 45 27 A 2.0002 2.0002 0 1 0 45 23 L 5 23 z M 5 38 A 2.0002 2.0002 0 1 0 5 42 L 45 42 A 2.0002 2.0002 0 1 0 45 38 L 5 38 z"></path>
      </svg>
    </section>
  </section>
</main>


<style>
  h3{
    display: flex;
    align-items: center;
    margin-left:15px;
  }
  main{
    width:98%;
    height:15%;
    max-height:45px;
    min-height:40px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color:black;
    border-radius:7px;
    margin-top:7px;
  }

  section#options{
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    width:15%;
    max-width:225px;
    min-width:150px;
  }
  section.icon{
    background-color: grey;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow:hidden;
  }
  svg{
    background-color:black;
    fill:grey;
  }

  svg:hover{
    fill:turquoise;
  }
</style>
