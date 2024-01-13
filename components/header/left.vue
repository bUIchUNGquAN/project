<template>
  <div class="lg:px-72 items-center justify-between flex text-left shadow-lg">
    <div class="flex items-center justify-between w-full">
      <div class="flex flex-shrink-0 items-center">
        <img class="w-12 h-12 rounded-lg" src="/assets/logo.png" />
        <p class="font-bold text-gray-900 text-xl dark:text-white mx-6 mt-2">
          Happy paws
        </p>
      </div>
      <div class="h-full items-center hidden sm:flex sm:ml-6 sm:ml-12">
        <NuxtLink to="/">
          <UButton
            label="Home"
            variant="ghost"
            class="px-4 py-4 mx-2 dark:text-white text-black font-bold text-xl"
          ></UButton>
        </NuxtLink>

        <NuxtLink to="/index2">
          <UButton
            label="Adopt Now"
            variant="ghost"
            class="px-4 py-4 mx-2 text-black dark:text-white font-bold text-xl"
          >
          </UButton>
        </NuxtLink>

        <UButton
          label="Try Now"
          variant="ghost"
          class="px-4 py-4 mx-2 text-black dark:text-white font-bold text-xl"
        >
          Try Now <UIcon name="i-bxs-tree" dynamic />
        </UButton>
      </div>
    </div>

    <div class="flex h-24 py-8 px-8">
      <!-- <NuxtLink to="/">
      
                          <UButton label="Home"  variant="ghost" class="px-4 py-4 mx-2 text-black font-bold text-xl "></UButton>
                      </NuxtLink>
                      
                      <NuxtLink to="/index2">
                      <UButton label="Adopt Now"  variant="ghost" class="px-4 py-4 mx-2 text-black font-bold text-xl">
                          
                      </UButton>
                       </NuxtLink>
                      
                      <UButton label="Try Now" variant="ghost"  class="px-4 py-4 mx-2 text-black font-bold text-xl">
                          Try Now <UIcon name="i-bxs-tree" dynamic/> 
                      </UButton> -->
      <UButton label="" variant="ghost" color="dark:text-white" class="mx-3">
        <UIcon name="i-bxs-sun" dynamic />
      </UButton>
      <UButton
        label=""
        variant="ghost"
        color="dark:text-white"
        class="-mr-2 items-center relative"
      >
        <UIcon color="dark:text-white" name="i-bx-menu" dynamic />
      </UButton>
    </div>
  </div>
</template>
