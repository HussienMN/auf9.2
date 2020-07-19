<template>
  <div class="nav">
    <router-link to="/">
      <button class="button-1">Home</button>
    </router-link>
    <router-link to="/adresse">
      <button class="button-1">Adresse</button>
    </router-link>
    <router-link to="/kontakt">
      <button class="button-1">Kontakt</button>
    </router-link>
    <router-link to="/about">
      <button class="button-1">Über us</button>
    </router-link>
  </div>
</template>

<script>
export default {
  name: "NavComponent"
};
</script>

<style>
h2 {
  font-size: 40px;
}
.button-1 {
  border-radius: 8px;
  background-color: #98afc7;
  margin: 8px;
  font-weight: bold;
  border-style: double;
  display: ruby;
  height: 2rem;
  width: 100%;
}
</style>
