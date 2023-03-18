<script>
const moringToDos = ['Get out of bed','Make coffee','Read feeds','Have shower','Brush teeth','Get dressed','Leave for work','Get breakfast to go'];
</script>

    <h1>Morning todos</h1>
    <ul>
        {#each moringToDos as moringToDos}
        <li><strong>{moringToDos}</strong></li>
        {/each}
    </ul>