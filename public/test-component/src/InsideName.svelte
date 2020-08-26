
<svelte:options accessors/>

<script>
    export var name = "Jim";
</script>

<style>
    .special {
        font-style: italic;
        border: none;
        border-top: 2px solid #ccc;
        border-bottom: 2px solid #ccc;
        border-radius: 3px 3px 0 0;
    }
</style>

<div class="special">
    <h1>
        Dammit, {name}, I'm a doctor not a bricklayer
    </h1>
</div>
