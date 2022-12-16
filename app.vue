<script setup>
function raiseEvent() {
  window.dataLayer.push({ event: 'test', payload: Math.random() })
}
</script>

<template>
  <div>
    <button @click="raiseEvent">Click me to raise an event</button>
  </div>
</template>
