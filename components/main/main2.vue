<template>
    
    <div class="container mx-auto px-4 py-12 relative " >
       
        <!-- text -->
        <div class="">
            <MainText2></MainText2>
            <!-- img -->
                <div class=" -mx-4 flex flex-wrap justify-center   mt-12">
                    <div v-for="(x,index) in list" :key="index" class="pb-4  px-4 rounded-3xl w-full sm:w-8/12 md:w-6/12 lg:w-4/12 "> 
                        <img  src="/assets/main2-1.jpg" class=" w-[450px]   h-[500px] rounded-[55px]" alt="">
                
                        <UButton  color="red" class=" w-[450px] bottom-28 h-[60px] absolute justify-center">adsfasd </UButton>
                    </div>
                </div>       
        </div>  
    </div>
</template>

<script setup>


    const list= ref([1,2,3])
    const getData = async()=>{
        try{
            const {data} = await useFetch("/api/list")
            list.value=data.value
        }
        catch(e){

        }
        getData()
    }

    
    

</script>