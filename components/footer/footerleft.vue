<template>
    <div class="container mx-auto  ">
        <div class="grid grid-cols-4 gap-x-4 ">
            <div class="mx-4 flex flex-wrap items-center space-x-6 mt-24 space-y-14  ">
                <img src="/assets/logo.png" alt="" class="w-24 h-24 rounded-lg">
                <p class="font-bold text-gray-900 text-4xl mx-5 mt-2">Happy pows</p>
                <p class="text-gray-900 text-2xl mx-5 mt-2">Duis pharetra venenatis felis, ut tincidunt ipsum consequat nec. Fusce et porttitor libero, eu aliquam nisi. Nam finibus ullamcorper semper. </p>           
                <a href="#">
                    <UButton size='2xs' color="blue">
                        <UIcon  name="i-bxl-facebook" dynamic/>
                    </UButton>
                </a>
                <a href="#">
                    <UButton size='2xs' color="blue">
                        <UIcon  color="blue" name="i-bxl-twitter" dynamic/>
                    </UButton>
                </a>
                <a href="#">
                    <UButton  size='2xs' variant="ghost" color="gray">
                        <UIcon  name="i-bxl-discord" dynamic/>
                    </UButton>
                </a>
                <a href="#">
                    <UButton size='2xs' color="red">
                        <UIcon  name="i-bxl-youtube" dynamic/>
                    </UButton>
                </a>
                <div class="grid grid-rows-2">

                    <span class="text-xl text-gray-800 text-center">+1234 56-890</span>
                    <span class="text-xl text-gray-800">buichungquan@fantico.com</span>
                </div>
            </div>
            <div class=" grid grid-rows-4 gap-x-4 items-center justify-center  mb-24 pt-28 ">
                <p class="font-bold text-2xl">General</p>
                <p class="cursor-pointer hover:text-white text-2xl">FAQ</p>
                <p class="cursor-pointer  hover:text-white text text-2xl">News</p>
                <p class="cursor-pointer  hover:text-white text text-2xl">Careers</p>
                <p class="cursor-pointer  hover:text-white text text-2xl">Contact Us</p>     
            </div>
            <div class=" grid grid-rows-6 gap-x-6 items-center justify-center space-x-6  mb-24 pt-28 ">
                <p class="font-bold text-2xl">Links</p>
                <p class="cursor-pointer hover:text-white text-2xl">Adopt Now</p>
                <p class="cursor-pointer hover:text-white text text-2xl">Donate</p>
                <p class="cursor-pointer hover:text-white text text-2xl">Articles</p>
                <p class="cursor-pointer hover:text-white text text-2xl">Blog</p>     
                <p class="cursor-pointer hover:text-white text text-2xl">Volunteer</p>     
                <p class="cursor-pointer hover:text-white text text-2xl">Our Mission</p>     
            </div>
            <div class="mx-4 flex flex-wrap  items-center  mb-24 pt-28  text-2xl font-bold"> Gallery 
                <div class="grid grid-cols-3 gap-3">
                    <img v-for="(x,index) in list" :key="index" src="/assets/12.jpg" class="w-[220px] h-[130px] rounded-[20px] hover:shadow-lg" alt="">
                   
                </div>
            </div>
        </div>
        <p class="text-xm float-right">© 2002 - 2021. All Rights Reserved - Quan </p>
    </div>
</template>

<script setup>
    const list= ref([1,2,3,4,5,6])
</script>