<template>
  <div>
    <div class="w-100 text-white">
      <div class="container">
        <div class="flex py-8 justify-between items-center">
          <div class="flex items-center w-28">
            <img src="@/assets/img/circlose.png" class="w-100">
          </div>

          <div class="border-2 rounded-full px-2 py-1">
            <span class="text-base"><i class="fas fa-bars"></i></span>
          </div>
        </div>
      </div>
    </div>

    <div class="container py-24">
      <div class="flex md:flex-row flex-col justify-between items-center">
        <div class="mx-auto w-10/12 md:w-4/12 mx-auto md:me-24">
          <img class="md:block hidden" src="@/assets/img/logo-text.png" alt="">
          <img class="block md:hidden" src="@/assets/img/circle-white.png" alt="">
        </div>

        <div class="mx-auto w-6/12 md:w-6/12 md:me-24 my-24 md:my-0 md:mt-0">
          <img class="md:block hidden" src="@/assets/img/circle-white.png" alt="">
          <img class="block md:hidden" src="@/assets/img/logo-text.png" alt="">
        </div>

        <div class="w-full md:w-14 mt-16 md:mt-0">
          <div class="text-white flex md:flex-col items-center justify-center bg-black border border-circlose rounded-full py-3 md:py-12">
            <a class="mx-4 md:p-5 text-xl cursor-pointer"><span><i class="fab fa-instagram"></i></span></a>
            <a class="mx-4 md:p-5 text-xl cursor-pointer"><span><i class="fab fa-tiktok"></i></span></a>
            <a class="mx-4 md:p-5 text-xl cursor-pointer"><span><i class="fab fa-whatsapp"></i></span></a>
            <a class="mx-4 md:p-5 text-xl cursor-pointer"><span><i class="fab fa-youtube"></i></span></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeView',
}
</script>
