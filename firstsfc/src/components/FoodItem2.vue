<template>
  <div class="burgers">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Baga burger',
      message: 'I love Baga burger because its affordable and its grilled patties!'
    }
  }
};
</script>

<style>
  #app > div {
    border: dashed rgb(255, 0, 0) 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: rgb(255, 136, 0);
  }
</style>
