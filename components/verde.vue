<template>
  <div class="verde" :class="{ 'on': isOn }"></div>
</template>

<script>
export default {
  props: ['isOn']
}
</script>

<style>
.verde {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  margin-bottom: 10px;
  background-color: green;
}

.on {
  opacity: 0;
}
</style>