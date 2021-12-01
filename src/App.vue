<template>
  <div>Rick and Morty</div>
  <ListCharacters />
</template>

<script>
import ListCharacters from "@/components/ListCharacters";
export default {
  name: "App",
  components: {
    ListCharacters,
  },
};
</script>

<style lang="scss">
</style>
