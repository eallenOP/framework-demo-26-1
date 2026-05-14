<script>
    let { name = 'Web 1' } = $props();
</script>

<div>
    <img src="https://placehold.co/200" alt="Placeholder person">
    <aside>
        <h3>{name}</h3>
        <ul>
            <li>Hobby 1</li>
            <li>Hobby 2</li>
            <li>Hobby 3</li>
        </ul>
    </aside>
</div>

<style>
    div {
        color: #333;
        display: flex;
        gap: 1em;
        border: 1px solid #ddd;
        margin-bottom: 1em;
        padding: 1em;
        max-width: 400px;
    }
</style>