<template>
  <v-container>
    <h1>ProDuct Detail</h1>
    <h2>{{ productid }}. {{ description }}</h2>
  </v-container>
</template>

<script>
export default {
  data() {
    return {
      productid: this.$route.params.id,
      description: this.$route.params.description,
    };
  },
};
</script>

<style></style>
