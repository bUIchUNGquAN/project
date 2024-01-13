<template>
  <div class="bg-white">
    <!-- header -->
    <div class="lg:h-[108px]">
      <div class="w-full fixed z-20">
        <input type="checkbox" v-model="isDark" />
        <HeaderLeft></HeaderLeft>
      </div>
    </div>

    <!-- main -->
    <div class="h-full bg-green-100 dark:bg-slate-900">
      <MainShow></MainShow>
    </div>

    <!-- footer -->
    <div class="bg-green-100 dark:bg-slate-900 h-[100%]">
      <div class="mx-auto py-4 pb-12">
        <FooterFooterleft></FooterFooterleft>
      </div>
    </div>
  </div>
</template>
<script setup>
import { useDark, useToggle } from "@vueuse/core";

const isDark = useDark();
const toggleDark = useToggle(isDark);
</script>
