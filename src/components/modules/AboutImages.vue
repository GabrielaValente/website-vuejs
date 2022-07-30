<template>
  <div class="boxIcons">
    <div class="boxIcon boxIcon1"></div>
    <div class="boxIcon boxIcon2"></div>
    <div class="boxIcon boxIcon3"></div>
    <div class="boxIcon boxIcon4"></div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.boxIcons {
  display: flex;
}

.boxIcon {
  height: 250px;
  width: 250px;

  border-radius: 15px;
  margin: 0 20px 50px;

  background-size: cover;
  background-position: center;
}

.boxIcon1 {
  background-image: url("https://images.unsplash.com/photo-1528892952291-009c663ce843?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=644&q=80");
}

.boxIcon2 {
  background-image: url("https://images.unsplash.com/photo-1502685104226-ee32379fefbe?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80");
}

.boxIcon3 {
  background-image: url("https://images.unsplash.com/photo-1506277886164-e25aa3f4ef7f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=735&q=80");
}

.boxIcon4 {
  background-image: url("https://images.unsplash.com/photo-1531123414780-f74242c2b052?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80");
}
</style>
