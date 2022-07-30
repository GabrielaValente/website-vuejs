<template>
  <div class="image">
    <div class="back">
      <h1 class="mb-6">SISTEMA DE AQUISIÇÕES</h1>

      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia vitae
        distinctio unde eum delectus quod hic corrupti mollitia neque,
        consequuntur voluptatem, exercitationem magni temporibus quidem
        molestiae quasi minima itaque perferendis.
      </p>

      <div class="mt-6">
        <v-btn
          class="mr-3 primary--text"
          color="#E2EEFF"
          height="55px"
          rounded
          depressed
          >SAIBA MAIS</v-btn
        >
        <v-btn class="" color="primary" height="55px" rounded depressed
          >ENTRAR EM CONTATO</v-btn
        >
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({}),
};
</script>

<style>
.image {
  background: red;
  height: 100vh;
  width: 100%;
  background-image: url("../.././assets/img-bg.jpg");
  background-size: cover;
  background-position: center;
}

.back {
  color: #ffffff;
  background: rgba(0, 0, 0, 0.568);
  height: 100vh;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  padding: 0 28%;
}
</style>
