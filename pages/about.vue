<template>
  <v-bottom-sheet>
    <template v-slot:activator="{ props }">
      <v-btn v-bind="props" text="Click Me"></v-btn>
    </template>

    <v-card
        title="Bottom Sheet"
        text="Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ut, eos? Nulla aspernatur odio rem, culpa voluptatibus eius debitis dolorem perspiciatis asperiores sed consectetur praesentium! Delectus et iure maxime eaque exercitationem!"
    ></v-card>
  </v-bottom-sheet>
</template>

<script setup>
</script>

<style scoped>
h1 {
  color: #333;
}
</style>
