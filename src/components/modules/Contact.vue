<template>
  <div class="contact__container">
    <h1>
      <v-icon size="40">email</v-icon>
      Entre em contato conosco!
    </h1>
    <div class="contact__form">
      <div class="contact__form__left">
        <v-text-field label="Nome" outlined rounded></v-text-field>
        <v-text-field label="E-mail" outlined rounded></v-text-field>
        <v-text-field label="Telefone" outlined rounded></v-text-field>
        <v-text-field label="Mensagem" outlined rounded></v-text-field>
        <v-btn color="primary" width="120px" rounded depressed height="55px"
          >ENVIAR</v-btn
        >
      </div>

      <img
        class="rounded-lg"
        height="320px"
        src="../.././assets/contact-image.svg"
        alt=""
      />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.contact__container {
  padding: 40px 19%;
  width: 100%;
}

.contact__form {
  display: flex;
  width: 100%;
  padding: 50px 0;
}

.contact__form__left {
  width: 100%;
  margin: 0 20px 0 0;
}
</style>
