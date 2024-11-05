<template>
  <div class="rojo" :class="{ 'on': isOn }"></div>
</template>

<script>
export default {
  props: ['isOn']
}
</script>

<style>
.rojo {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  margin-bottom: 10px;
  background-color: red;
}

.on {
  opacity: 0;
}
</style>