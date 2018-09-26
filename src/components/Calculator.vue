<template>
  <div class="calculator">
    <div class="display">0.05324</div>
    <div class="">C</div>
    <div class="">+/-</div>
    <div class="">%</div>
    <div class="">/</div>
    <div class="">7</div>
    <div class="">8</div>
    <div class="">9</div>
    <div class="">x</div>
    <div class="">4</div>
    <div class="">5</div>
    <div class="">6</div>
    <div class="">-</div>
    <div class="">1</div>
    <div class="">2</div>
    <div class="">3</div>
    <div class="">+</div>
    <div class="zero">0</div>
    <div>.</div>
    <div>=</div>
  </div>
</template>

<script>
export default {
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.calculator {
  font-size: 14px;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(50px, auto);
}
.display{
  grid-column: 1 / 5;
  background-color: red;
}
.zero {
  grid-column: 1 / 3;
}
</style>
