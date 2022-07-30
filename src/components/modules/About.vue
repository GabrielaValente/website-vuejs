<template>
  <div class="hero__container">
    <v-icon size="55">account_circle</v-icon>
    <h2>QUEM SOMOS</h2>

    <div class="h__span__container">
      <span
        >Lorem ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis
        consectetur rerum adipisci, mollitia odio numquam placeat distinctio
        fuga velit at, nesciunt eum tempora exercitationem? Fugiat error illo
        maxime nemo voluptatem?</span
      >
    </div>

    <AboutImages />
  </div>
</template>

<script>
import AboutImages from "./AboutImages.vue";
export default {
  components: {
    AboutImages,
  },
};
</script>

<style>
.hero__container {
  display: flex;
  flex-direction: column;
  align-items: center;

  text-align: center;
  width: 100%;
}

.hero__container > h2 {
  margin: 0 0 25px 0;
}

.h__span__container {
  width: 750px;
  margin: 0 0 25px 0;
}

.h__search__container {
  width: 450px;
}
</style>
