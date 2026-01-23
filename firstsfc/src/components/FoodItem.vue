<template>
  <div class="chicken">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'McDonalds & Jollibee ',
      message: 'I love this two fast food chain because im a big fan of their fries, burger and chicken!'
    }
  }
};
</script>

<style>
  #app > div {
    border: dashed #fffb00 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: red;
  }
</style>