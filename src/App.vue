<template>
  <div class="container">
    <h1>Rick And Morty</h1>
  </div>
  <filterByStatus />
  <ListCharacters />
</template>

<script>
import ListCharacters from "@/components/ListCharacters";
import FilterByStatus from "@/components/FilterByStatus";
export default {
  name: "App",
  components: {
    ListCharacters,
    FilterByStatus,
  },
};
</script>

<style lang="scss">
:root {
  --background-body: #24282f;
  --background-card: #3c3e44;
  --text-white: #ffffff;
  --text-gray: #c0c0c0;
  --text-orange: #ff9800;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  background: var(--background-body);
  color: var(--text-white);
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
h1 {
  margin-bottom: 3rem;
  text-align: center;
}
.container {
  width: 980px;
  max-width: 90%;
  margin: 5rem auto;
}
img {
  width: 100%;
}
li:hover {
  cursor: pointer;
}
</style>
