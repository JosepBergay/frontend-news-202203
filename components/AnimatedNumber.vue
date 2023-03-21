<script setup lang="ts">
import { ref, reactive, watch, watchEffect } from 'vue'
import gsap from 'gsap'

const props = defineProps<{ n: number }>()
// const number = ref(0)
const tweened = reactive({
  number: 0,
})

watchEffect(() => {
  gsap.to(tweened, { duration: 5, number: Number(props.n) || 0 })
})
</script>

<template>
  <span>{{ tweened.number.toFixed(0) }}</span>
</template>
