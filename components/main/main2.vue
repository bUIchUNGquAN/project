<template>
    <div class=" container mx-auto" >
        <!-- text -->
        <div class="">
            <MainText2></MainText2>
        </div>  
        <!-- img -->
            <div class="relative flex flex-wrap justify-center mt-12">
                <div v-for="(x,index) in list" :key="index" class="rounded-3xl w-full sm:w-8/12 md:w-6/12 lg:w-4/12">
                    <img  src="/assets/main2-1.jpg" class="relative w-[450px] h-[500px] rounded-[55px]" alt="">
                    <UButton variant="ghost" color="red" class="absolute bottom-5 w-[410px] h-[60px] justify-center">donate</UButton>
                </div>
            </div>       
    </div>
</template>

<script setup>
    const list= ref([1,2,3])
</script>