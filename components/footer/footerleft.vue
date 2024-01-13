<template>
    <div class="container mx-auto  ">
        <div class="flex flex-wrap relative">
            <div class="-mx-4 flex flex-col flex-wrap items-center pl-4 pr-8 py-4 md:flex-col md:flex-nowrap -mt-4 lg:items-start lg:w-1/3">
                <div class="flex flex-wrap">
                    <img src="/assets/logo.png" alt="" class="w-24 h-24 rounded-lg">
                    <p class="font-bold text-gray-900 text-4xl mx-5 mt-8">Happy pows</p>
                </div>
                <div class="mt-2 text-center w-full lg:text-left">
                    <p class="text-gray-900 text-2xl mx-5 mt-2">Duis pharetra venenatis felis, ut tincidunt ipsum consequat nec. Fusce et porttitor libero, eu aliquam nisi. Nam finibus ullamcorper semper. </p>           
                </div>
                    <div class="inline-flex  mt-3 space-x-6">
                        <div class="flex lg:flex-wrap space-x-4">
    
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
                        </div>
                    </div>
                    <div class="my-6 text-center ">
                            <span class="font-bold text-gray-900 ">+1234 56-890</span><br>  
                            <span class="font-bold text-gray-900">buichungquan@fantico.com</span>   
                    </div>
                </div>
                
                 <div class=" flex flex-col items-center p-4 w-full sm:w-1/2 md:flex-1 md:w-1/3 lg:items-start ">
                    <p class="font-bold text-2xl">General</p>
                    <p class="cursor-pointer  dark:text-white text-2xl">FAQ</p>
                    <p class="cursor-pointer  dark:text-white text text-2xl">News</p>
                    <p class="cursor-pointer  dark:text-white text text-2xl">Careers</p>
                    <p class="cursor-pointer  dark:text-white text text-2xl">Contact Us</p>     
                </div>
                <div class="flex flex-col items-center p-4 w-full sm:w-1/2 md:flex-1 md:w-1/3 lg:items-start ">
                    <p class="font-bold text-2xl">General</p>
                    <p class="cursor-pointer  dark:text-white text-2xl">FAQ</p>
                    <p class="cursor-pointer  dark:text-white text text-2xl">News</p>
                    <p class="cursor-pointer  dark:text-white text text-2xl">Careers</p>
                    <p class="cursor-pointer  dark:text-white text text-2xl">Contact Us</p>     
                </div>
                <div class="flex flex-cols items-center p-4 w-full md:w-1/3" >
                <p class="font-bold text-gray-800">Galary</p>
                <div class="-mx-2 flex flex-wrap items-center lg:mt-2">
                    <div v-for="(x,index) in list" :key="index" class="p-2 w-1/2 sm:w-4/12 flex flex-wrap gap-6" >
                        <img src="https://gaixinhbikini.com/wp-content/uploads/2023/03/anh-gai-sexsy.jpg" alt="" class="block hover:opacity-75 overflow-hidden rounded-xl"> 
                        
                    </div>
                </div>
               </div>
                
            </div>
            <p class="text-xm float-right">© 2002 - 2021. All Rights Reserved - Quan </p> 
        </div>
  
</template>

<script setup>
    const list= ref([1,2,3,4,5,6
      

    ])
</script>