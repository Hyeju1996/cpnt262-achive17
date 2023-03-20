<script>
/************/
/* Player 1 */
/************/

// Player 1 general
const player1Name = 'Ryan Reynolds';
const player1Race = 'human';
const player1Class = 'rogue';
let player1Level = 1;
let player1Health = 8;

// Player 1 stats
let player1Strength = 7;
let player1Dexterity = 12;
let player1Constitution = 8;
let player1Intelligence = 9;
let player1Wisdom = 9;
let player1Charisma = 11;

// Player 1 effects
let player1Poisoned = true;

// Player 1 items
let player1Backpack = [
    'rusty knife',
    'gem',
    'journal'
  ];

/************/
/* Player 2 */
/************/

// Player 2 general
const player2Name = 'Gyda';
const player2Race = 'dwarf';
const player2Class = 'fighter';
let player2Level = 1;
let player2Health = 12;

// Player 2 stats
let player2Strength = 11;
let player2Dexterity = 7;
let player2Constitution = 11;
let player2Intelligence = 7;
let player2Wisdom = 8;
let player2Charisma = 7;

// Player 2 effects
let player2Poisoned = false;

// Player 2 items
let player2Backpack = [
  'sword',
  'leather armour',
  'rations'
];

/************/
/* Player 3 */
/************/

// Player 3 general
const player3Name = 'Anna';
const player3Race = 'elf';
const player3Class = 'wizard';
let player3Level = 1;
let player3Health = 9;

// Player 3 stats
let player3Strength = 8;
let player3Dexterity = 9;
let player3Constitution = 8;
let player3Intelligence = 11;
let player3Wisdom = 10;
let player3Charisma = 8;

// Player 3 effects
let player3Poisoned = true;

// Player 3 items
let player3Backpack = [
  'staff',
  'cloak',
  'spell book'
];
</script>


<main>

<h1>List of Players</h1>
<ul>
    <li>nam: {player1Name}
    <li>race{player1Race}</li>
    <li>class: {player1Class}</li>
    <li>level:{player1Level}</li>
    <li>health:{player1Health}</li>
    <li>Poisned: {player1Poisoned}</li>
</ul>
<h2>Backpack of list</h2>
<li>Backpack{player1Backpack}</li>


<h2>List of Playes 2</h2>
<ul>
    <li>name: {player2Name}</li>
    <li>race: {player2Race}</li>
    <li>class: {player2Class}</li>
    <li>level: {player2Level}</li>
    <li>health: {player2Health}</li>
    <li>poisoned: {player2Poisoned}</li>
</ul>
<h2>backpack of list</h2>
<ul>
<li>backpack: {player2Backpack}</li>
</ul>

<h2>List of player3</h2>
<ul>
    <li>Name:{player3Name}</li>
    <li>race:{player3Race}</li>
    <li>class:{player3Class}</li>
    <li>level:{player3Level}</li>
    <li>health: {player3Health}</li>
</ul>
<h2>Refactor:3</h2>
<ul>
<li>my name is {player3Name}</li>
<li>I am {player3Race}</li>
<li>my level is {player3Class}</li>
<li>{player3Level}</li>
<li>{player3Health}</li>
</ul>

</main>