<template>
    <div>
        <Header />
        <Hsilder />
        <Novice />
        <Borrow />
        <Money />
        <Product />
        <Life />
        <Footer />
        <Navbar />
    </div>
</template>

<script>
import Header from "../public/header.vue"
import Hsilder from "../home/hslider.vue"
import Footer from "../public/footer.vue"
import Navbar from "../public/navbar.vue"
import Novice from "./novice.vue"
import Borrow from "./borrow.vue"
import Money from "./money.vue"
import Product from "./product.vue"
import Life from "./life.vue"

export default {
    components: {
        Header,
        Hsilder,
        Novice,
        Borrow,
        Money,
        Product,
        Life,
        Footer,
        Navbar,
    },

}
</script>
