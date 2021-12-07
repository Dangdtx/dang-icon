<script setup>
import '../src/assets/font/iconfont.css'
defineProps({
  iconName: String,
})
</script>
<template>
  <i :class="['iconfont',iconName]"></i>
</template> 
