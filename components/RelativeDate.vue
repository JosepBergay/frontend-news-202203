<script setup lang="ts">
import dayjs from 'dayjs'
import relativeTime from 'dayjs/plugin/relativeTime'

dayjs.extend(relativeTime)

defineProps<{ date: string | number | Date }>()

</script>

<template>
  <span>{{ dayjs().to(dayjs(date)) }}</span>
</template>
