<script setup>
import HeroImage from "../components/HeroImage.vue";
import TextCards from "../components/TextCards.vue";
import BookFetch from "../components/BookFetch.vue";
import TheFooter from "../components/TheFooter.vue";
</script>

<template>
  <HeroImage />

  <TextCards />
  <BookFetch />

  <div id="footer">
    <TheFooter />
  </div>
</template>
<script></script>

<style scoped>
#footer {
  background-color: rgb(225, 220, 197);
  padding: 20px;
  position: sticky;
}
</style>
