<template>
  <div class="pb-24 pt-12">
    <div class="container mx-auto px-4 relative">
      <div class="px-4 text-center w-full">
        <!-- text -->
        <MainText4></MainText4>
      </div>
      <div class="flex flex-wrap -mx-4 justify-center">
        <a
          v-for="(x, index) in listImg"
          :key="index"
          href="#"
          class="w-full md:w-6/12 lg:w-4/12 xl:w-3/12"
        >
          <div
            class="m-3 text-neutral-900 dark:text-neutral-100 bg-neutral-50 dark:bg-neutral-900 px-6 py-12 rounded-3xl shadow-xl text-center"
          >
            <img src="/assets/bella.jpg" alt="" class="rounded-lg" />
            <h6 class="font-bold dark:text-white text-xl">girl</h6>
            <h6 class="font-bold dark:text-white text-sm">sexxy</h6>
            <div>
              <UButton
                label="Adopt Now"
                variant="ghost"
                color="dark:text-white"
              >
                Adopt Now <UIcon name="i-bxs-heart" dynamic></UIcon>
              </UButton>
            </div>
          </div>
        </a>
      </div>
    </div>
  </div>
</template>

<script setup>
const listImg = ref([1, 2, 3, 4]);
// const list = ref([
//     {
//         name:'roak',
//         tilte:'dora',
//         url:'https://2sao.vietnamnetjsc.vn/images/2017/01/20/08/24/148486332991054v4.jpg'
//     },
//     {
//         name:'bi',
//         tilte:'dora',
//         url:'https://kenh14cdn.com/203336854389633024/2022/1/18/photo-1-1642487475390824147792.jpg'
//     },
//     {
//         name:'roak',
//         tilte:'dora',
//         url:'https://genk.mediacdn.vn/2019/11/16/photo-1-157391861987012470781.jpg'
//     },
//     {
//         name:'roak',
//         tilte:'dora',
//         url:'https://gaixinhbikini.com/wp-content/uploads/2022/09/anh-gai-sexsy.jpg'
//     },
// ])
</script>
