<script setup>
  import own from './ownButton.vue';
</script>

<template>
  <own
    class="accept-button"
  >
    <slot> 
      ACCEPT
    </slot>
  </own>
</template>


<style scoped>
.accept-button :deep(.own-button)
{
  background-color  : #4CAF50 !important;
  outline-color     : green !important;
}
.accept-button :deep(.own-button:hover)
{
  background-color: green !important;
}
</style>