
<template>
  <div class="min-h-[100vh]">
    <Header></Header>
    <div class="grid md:grid-cols-[1fr,3fr] grid-cols-[1fr,1fr]">
      <List />
      <Map />
    </div>
  </div>
</template>

<script setup lang="ts">

import Header from "@/components/Header.vue"
import List from "@/components/List.vue"
import Map from "@/components/Map.vue"

</script>


<style>
@import url("https://fonts.googleapis.com/css2?family=Oswald&family=Roboto&display=swap");

body {
  margin: 0;
  font-family: "Oswald", sans-serif;
  font-family: "Roboto", sans-serif;
}
</style>
