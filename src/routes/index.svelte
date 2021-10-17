<script>
    import Color from '$lib/Color.svelte';
    let colorName = 'Pink';
    let colorNames = 'Blue';
</script>

<div>
    <h1 class="text-primary">Play with Colors</h1>
</div>

<div>
    <input bind:value={colorName} />
    <Color color={colorName} />
</div>

<div>
    <input bind:value={colorNames} />
    <Color color={colorNames} />
</div>

<style>
    input {
   	 padding: 0.5em;
   	 text-align: center;
    }
    div {
   	 text-align: center;
   	 margin: 3em auto;
    }
</style>


