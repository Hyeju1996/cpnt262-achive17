<script>
  let animalId = 1;
   
   const handleChange = function(event) {
     console.log(event.target);
     if (event.target.value === 'sky') {
       animalId = 237;
     } else if (event.target.value === '') {
       animalId = 433;
     } else if (event.target.value === 'monkey') {
       animalId = 783;
     } else if (event.target.value === 'bird') {
       animalId = 1024;
     } else if (event.target.value === 'walrus') {
       animalId = 1084;
     } else {
       animalId = 1;
     }
   }
</script>
<h1>The button value attribute</h1>

<main>
<label for="anmial">Choose an Animal</label>
  <select on:change={handleChange} name="animal" id="animal">
    <option value="">Please select an view</option>
    <option value="puppy">Puppy</option>
    <option value="bear">Bear</option>
    <option value="monkey">Monkey</option>
    <option value="bird">Bird</option>
    <option value="walrus">Walrus</option>
  </select>
  <h1>Animal of the Day</h1>
  <img src="https://picsum.photos/id/{animalId}/500/500" alt="Random Lorem Picsum">
</main>


Update:
  <style>
    button {
        color: blue;
    }
  </style>