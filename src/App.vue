<template>
  <Header></Header>
  <Perspective></Perspective>
  <Footer></Footer>
</template>

<script>
import Header from "./components/Header.vue"
import Perspective from "./components/Perspective.vue"
import Footer from "./components/Footer.vue"
export default {
  name: "App",
  components: {
    Header,
    Perspective,
    Footer,
  },
  data() {
    return {}
  }
}
</script>

