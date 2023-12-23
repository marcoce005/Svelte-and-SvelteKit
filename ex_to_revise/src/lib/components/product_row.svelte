<script>
    export let products = [];
</script>

{#each products as p}
    <div class="row">
        <div class="type">{p.type}</div>
        <div class="stock {p.stock ? "green" : "red"}">{p.stock ? "IN STOCK" : "OUT OF STOCK"}</div>
        <div class="prize">${p.prize}</div>
    </div>
{/each}

<style>
    .row {
        width: 50%;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        margin-bottom: 1%;
        font-size: 18px;
    }

    .stock {
        font-weight: bolder;
    }

    .green {color: green;}
    .red {color: red;}
</style>    