<template>
  <div id="app">
    <div class="container">
        <Navbar></Navbar>
        <Showcase></Showcase>
        <Features></Features>
    </div>
    <Download></Download>
    <Cta></Cta>
    <Footer></Footer>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar";
import Showcase from "@/components/Showcase";
import Features from "@/components/Features";
import Download from "@/components/Download";
import Cta from "@/components/Cta";
import Footer from "@/components/Footer";

export default {
  name: "App",
  components: {
    Navbar,
    Showcase,
    Features,
    Download,
    Cta,
    Footer
  },
};
</script>

<style lang="scss">
@import './styles/app.scss';
</style>
