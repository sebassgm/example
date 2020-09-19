<template>
  <v-container>
    <v-text-field v-model="label" label="Label"></v-text-field>
    <v-btn class="mx-2" fab dark color="indigo">
      <v-icon dark>mdi-plus</v-icon>
    </v-btn>
  </v-container>
</template>
<script>
export default {
  name: "Search",
};
</script>