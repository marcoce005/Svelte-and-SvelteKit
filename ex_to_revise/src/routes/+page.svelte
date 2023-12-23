<script>
    import SearchBar from "../lib/components/search_bar.svelte";
    import ProductTable from "../lib/components/product_table.svelte";

    function search_in_list(e) {
        console.log(e.detail);
    }
</script>

<section>
    <SearchBar on:search={search_in_list}/>
    <ProductTable />
</section>

<style>
    section {
        margin-left: 5%;
        margin-top: 5%;
    }
</style>