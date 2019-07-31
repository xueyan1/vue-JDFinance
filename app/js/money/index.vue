<template>
    <div>
        <Header />
        <Mslider />
        <Footer />
        <Navbar cname="mfooter" />
    </div>
</template>

<script type="text/ecmascript-6">
import Header from "../../js/public/header.vue"
import Footer from "../../js/public/footer.vue"
import Navbar from "../../js/public/navbar.vue"
import Mslider from "./mslider.vue"

export default {
    components: {
        Header,
        Footer,
        Navbar,
        Mslider,
    },
    data() {
        return {

        }
    },
}
</script>

<style lang="scss" module>
.mfooter {
  margin: 0 !important;
  ul {
    li:first-child {
      display: none;
    }
  }
}
</style>
