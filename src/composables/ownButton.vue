<template>
  <button
    class="own-button"
    type="button"
  >
    <slot> 
    </slot>
  </button>
</template>

<script setup>
</script>

<style scoped>
.own-button
{
  background-color  : azure;
  outline-color     : lightblue;
  color             : black;
  margin            : 2px;
  padding           : 5px;
  border-radius     : 15px;
  border            : 0;
  box-shadow        : 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  outline-style     : solid;
  min-width         : 100px;
  max-width         : 150px;
}
.own-button:hover
{
  cursor: pointer;
}
</style>