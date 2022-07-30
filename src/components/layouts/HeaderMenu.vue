<template>
  <div class="menu__list">
    <span class="list__item" v-for="(item, index) in menuList" :key="index">
      <v-icon class="mr-2" size="14">{{ item.icon }}</v-icon>
      {{ item.name }}
    </span>
  </div>
</template>

<script>
export default {
  data: () => ({
    // "Institucional", "Compras Públicas", "Contratos"
    menuList: [
      { icon: "account_balance", name: "Institucional" },
      { icon: "credit_card", name: "Compras Públicas" },
      { icon: "speaker_notes", name: "Contratos" },
      { icon: "find_in_page", name: "Catálogo" },
      { icon: "book", name: "Editais" },
      { icon: "analytics", name: "Licitações" },
    ],
  }),
};
</script>

<style>
.menu__list {
  display: flex;
  align-items: center;
}

.menu__list > span {
  margin: 0 0 0 20px;
  display: flex;
  align-items: center;
}

.list__item:hover {
  cursor: pointer;
  border-bottom: 2px solid rgb(255, 255, 255);
}
</style>
