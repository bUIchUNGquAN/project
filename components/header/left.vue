<template>
        <div class=" px-72 items-center justify-between flex text-left shadow-lg">
           
            <div class="flex py-8 px-8">
                <img class="w-12 h-12 rounded-lg" src="/assets/logo.png">
                <p class="font-bold text-gray-900 text-xl mx-5 mt-2">Happy paws</p>
            </div>
    
            <div class="flex py-8 px-8 ">
                <NuxtLink to="/">

                    <UButton label="Home"  variant="ghost" class="px-4 py-4 mx-2 text-black font-bold text-xl "></UButton>
                </NuxtLink>
                
                <NuxtLink to="/index2">
                <UButton label="Adopt Now"  variant="ghost" class="px-4 py-4 mx-2 text-black font-bold text-xl">
                    
                </UButton>
            </NuxtLink>
                
                    <UButton label="Try Now" variant="ghost"  class="px-4 py-4 mx-2 text-black font-bold text-xl">
                        Try Now <UIcon name="i-bxs-tree" dynamic/> 
                    </UButton>
                <UButton label="" variant="ghost" color="black" class="px-4 py-4 mx-2 text-xl">
                    <UIcon name="i-bxs-sun" dynamic />
                </UButton>
                <UButton label="" variant="ghost" color="black" class="px-4 py-4 mx-2 text-xl ">
                    <UIcon name="i-bx-menu" dynamic />
                </UButton>
            </div>
           
        </div>
</template>
<script setup>
const next = () =>{
    const router = useRouter()
    
}
</script>