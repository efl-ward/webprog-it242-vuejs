<template>
  <div class="rambutan">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'R',
      message: 'I like Rambutan'
    }
  }
};
</script>

<style>
  .rambutan {
    border: dashed black 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: rgb(223, 147, 223);
  }
</style>