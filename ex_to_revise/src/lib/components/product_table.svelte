<script>
    import ProductCategory from "../components/product_category.svelte";
    import ProductRow from "../components/product_row.svelte";

    let vegetables = [
        {
            type: "Lettuce",
            stock: true,
            prize: 2.99,
        },
        {
            type: "Carrots",
            stock: true,
            prize: 1.99,
        },
    ];

    let breads = [
        {
            type: "Premium Burger Buns",
            stock: true,
            prize: 4.99,
        },
    ];

    let meat = [
        {
            type: "Mince",
            stock: true,
            prize: 12.99,
        },
    ];

    let spreads = [
        {
            type: "Mayonnaise",
            stock: true,
            prize: 3.99,
        },
        {
            type: "Premium Sauce",
            stock: false,
            prize: 13.99,
        },
    ];
</script>

<section>
    <div>
        <ProductCategory type="VEGETABLE" />
        <ProductRow products={vegetables} />
    </div>
    <div>
        <ProductCategory type="BREADS" />
        <ProductRow products={breads} />
    </div>
    <div>
        <ProductCategory type="MEAT" />
        <ProductRow products={meat} />
    </div>
    <div>
        <ProductCategory type="SPREADS" />
        <ProductRow products={spreads} />
    </div>
</section>


<style>
    div {
        margin-top: 3%;
    }
</style>