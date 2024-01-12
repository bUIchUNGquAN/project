<template>
    <div class="pb-24 pt-12">
        <div class="container mx-auto px-4 relative">

            <div class="px-4 text-center w-full">
                <!-- text -->
                <MainText4></MainText4>
            </div>
            <div class="-mt-4 flex flex-cols mx-auto pt-8 px-4 relative">
                <div class="-mx-4 grid grid-cols-4 gap-4 items-center justify-center mb-4" >
                    <a  v-for="(x,index) in listImg" :key="index" href="#" class="w-full flex flex-wrap text-center">
                        <div class="m-3 text-neutral-900 dark:text-neutral-100 bg-neutral-50 dark:bg-neutral-900 px-6 py-12 rounded-3xl shadow-xl text-center">
                            <img src="/assets/bella.jpg" alt="">
                            <h6 class="font-bold text-xl">rokaka</h6>
                            <h6 class="font-bold text-sm">dog</h6>
                            <div>
                                <UButton label="Adopt Now" variant="ghost" color="dark:text-white">
                                    Adopt Now   <UIcon name="i-bxs-heart" dynamic></UIcon>
                                </UButton>
                            </div>
                        </div>
                    </a>
                </div>
            </div>
        </div>
     
    </div>
</template>

<script setup>
    const listImg =ref([1,2,3,4,5,6,7,8
       
    ])
</script>