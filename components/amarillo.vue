<template>
  <div class="amarillo" :class="{ 'onamarillo': isOn }"></div>
</template>

<script>
export default {
  props: ['isOn']
}
</script>
  
<style>
.amarillo {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  margin-top: 10px;
  background-color: yellow;
}

.onamarillo {
  background-color: rgba(255, 255, 0, 0.1);
}
</style>