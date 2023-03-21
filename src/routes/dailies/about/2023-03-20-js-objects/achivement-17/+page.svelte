<script>
    let counter = 0;
    const countList =[];
     


    const handleClick = ( ) => {
      counter++;
      counterList.push(counter);
      console.log(counter);

      if (counter % 3 ===0){

      }
    }
</script>


<main>
    <h1>Push of a Button</h1>
    <button>on:click= {handleClick}</button>
    <ul>
        {#each countList as item}
        <li>{item}</li>
        {/each}
    </ul>
</main>