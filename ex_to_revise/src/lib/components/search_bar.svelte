<script>
    import { createEventDispatcher } from "svelte";

    const dispatch = createEventDispatcher();

    let product;
    let disponibility = false;
</script>

<svelte:head>
    <link
        rel="stylesheet"
        href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200"
    />
</svelte:head>

<section>
    <div class="search-box">
        <input type="text" placeholder="Search..." bind:value={product}/>
        <span
            class="material-symbols-outlined icon"
            on:click={() =>
                dispatch("search", {
                    'product': product,
                    'disponibility': disponibility,
                })}>search</span
        >
    </div>

    <div class="check">
        <input type="checkbox" bind:checked={disponibility}/>
        <label for="desc-checkbox">Soli prodotti disponibili</label>
    </div>
</section>

<style>
    .search-box {
        width: 30%;
        display: grid;
        grid-template-columns: 90% 10%;
        padding: 2%;
        border-radius: 7px;
        background-color: gray;
        column-gap: 10px;
    }

    input {
        background-color: white;
        border: none;
        font-size: 20px;
        border-radius: 5px;
    }

    .icon {
        border: 1px solid black;
        border-radius: 5px;
        color: white;
        padding: 1%;
        text-align: center;
    }

    .icon:hover {
        cursor: pointer;
    }

    .check {
        margin-top: 2%;
        font-size: 20px;
    }
</style>
