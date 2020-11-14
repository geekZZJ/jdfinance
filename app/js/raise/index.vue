<template lang="html">
    <div>
        <Heador/>
        <Slider/>
        <Daily/>
        <In/>
        <More/>
        <Footer cname="mfooter"/>
        <Navbar/>
    </div>
</template>

<script>
import Heador from "../public/header.vue"
import Footer from "../public/footer.vue"
import Navbar from "../public/navbar.vue"
import Slider from "./rslider.vue"
import Daily from "./daily.vue"
import In from "./in.vue"
import More from "./more.vue"
export default {
    components: {
        More,
        In,
        Daily,
        Navbar,
        Footer,
        Heador,
        Slider,
    },
}
</script>

<style lang="scss">
  .mfooter{
    ul{
      li:first-child{
        display: none;
      }
    }
  }
</style>
