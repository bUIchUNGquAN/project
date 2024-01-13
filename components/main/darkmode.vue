<script setup>
import { useDark, useToggle } from "@vueuse/core";

const isDark = useDark();
const toggleDark = useToggle(isDark);
</script>

<template>
  <div
    class="grid place-content-center h-screen bg-slate-400 dark:bg-slate-900"
  >
    <input type="checkbox" v-model="isDark" />
  </div>
</template>
