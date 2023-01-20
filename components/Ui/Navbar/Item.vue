<script setup lang="ts">
defineProps<{
  title: string
  to: string | object
}>()

const defaultClass = 'py-3.5 font-semibold cursor-pointer'
const activeClass = 'text-purBlue border-b-3 border-purBlue pt-3.5 pb-2.5'
const inactiveClass = 'py-3.5'
const hoverClass = 'hover:py-1.5 hover:my-2 hover:px-3.5 hover:bg-coolBlue hover:text-purBlue'
</script>

<template>
  <li :class="`${defaultClass}`">
    <NuxtLink :to="to">
      {{ title }}
    </NuxtLink>
  </li>
</template>
