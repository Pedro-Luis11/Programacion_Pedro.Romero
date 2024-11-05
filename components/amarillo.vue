<template>
  <div class="amarillo" :class="{ 'on': isOn }"></div>
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
  margin-bottom: 10px;
  background-color: yellow;
}

.on {
  opacity: 0;
}
</style>