<template>
  <div>
    <button class="button-1">Home</button>
    <button class="button-1">Kurse</button>
    <button class="button-1">Adresse</button>
    <button class="button-1">Kontakt</button>
  </div>
</template>

<script>
export default {
  name: "SideMenu"
};
</script>

<style scoped>
.button-1 {
  border-radius: 8px;
  background-color: #98afc7;
  margin: 8px;
  font-weight: bold;
  border-style: double;
  height: 2rem;
  width: 45%;
  display: block;
  overflow-wrap: break-word;
  word-wrap: break-word;
}
</style>