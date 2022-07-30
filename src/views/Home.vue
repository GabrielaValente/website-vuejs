<template>
  <div>
    <Header />

    <ImageContainer />

    <v-container>
      <About class="my-12" />

      <Options />
      <Contact />
    </v-container>

    <Footer />
  </div>
</template>

<script>
import Header from "@/components/layouts/Header.vue";
import ImageContainer from "@/components/modules/Image.vue";
import About from "@/components/modules/About.vue";
import Options from "@/components/modules/Options.vue";
import Contact from "@/components/modules/Contact.vue";
import Footer from "@/components/layouts/Footer.vue";

export default {
  components: {
    Header,
    ImageContainer,
    About,
    Options,
    Contact,
    Footer,
  },
};
</script>

<style></style>
