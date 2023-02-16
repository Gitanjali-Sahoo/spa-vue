<script setup>
import FormValidate from "../components/FormValidate.vue";
import TheFooter from "../components/TheFooter.vue";
</script>

<template>
  <FormValidate />
  <div id="footer">
    <TheFooter />
  </div>
</template>

<style scoped>
#footer {
  background-color: rgb(225, 220, 197);
  padding: 20px;
  position: sticky;
}
</style>
