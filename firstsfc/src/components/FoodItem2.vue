<template>
  <div class="grapes">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Melon and Grapes',
      message: 'I like melon and grapes'
    }
  }
};
</script>

<style>
  .grapes {
    border: dashed black 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: lightblue;
  }
</style>