<template>
  <div class="bg-white dark:bg-black">
    <!-- header -->
    <div class="lg:h-[108px]">
      <div class="w-full fixed z-10">
        <input type="checkbox" v-model="isDark" />
        <HeaderLeft></HeaderLeft>
      </div>
    </div>

    <!-- main -->
    <div class="h-full">
      <div>
        <MainMain1></MainMain1>
      </div>
      <div>
        <MainMain2></MainMain2>
      </div>
      <div>
        <MainMain3></MainMain3>
      </div>
      <div class="bg-slate-400 dark:bg-green-700">
        <MainMain4></MainMain4>
      </div>
      <div>
        <MainMain5></MainMain5>
      </div>
    </div>

    <!-- footer -->
    <div class="bg-green-100 dark:bg-black h-[100%]">
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
