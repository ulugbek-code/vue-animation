<template>
  <header>
    <h1>{{ title }}</h1>
    <p>hello</p>
  </header>
</template>

<script>
export default {
  props: ['title']
};
</script>

<style scoped>
header {
  width: 100%;
  height: 5rem;
  background-color: hsl(235, 100%, 20%);
  display: flex;
  justify-content: center;
  align-items: center;
}

header h1,p {
  color: white;
  margin: 0;
}
</style>
