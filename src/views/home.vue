<script lang="ts" setup>
import Advantages from './Advantages.vue'
import Cases from './Cases.vue'
import Indicators from './Indicators.vue'
import Attack from './Attack.vue'
import Order from './Order.vue'
</script>

<template>
   <div>
      <div
         class="lg:container lg:mx-auto flex gap-1 items-center overflow-hidden bg-primary lg:rounded-tr-3xl lg:rounded-bl-3xl !mb-[72px] max-sm:flex-col-reverse">
         <img src="@/assets/img/user.png" alt="">
         <img class="hidden" src="@/assets/img/userlg.png" alt="">
         <div class="max-sm:mt-[72px] max-sm:mb-[32px]">
            <h1 class="text-white max-lg:text-[40px]">{{ $t('Security') }}</h1>
            <p class="mt-4 mb-8 text-white text-xl md:mr-[170px]">
               {{ $t('biometricIdentification') }}
            </p>
            <button class="px-8 py-4 text-white bg-danger">{{ $t('ConnectNow') }}</button>
         </div>
      </div>
      <Advantages />
      <Cases />
      <Indicators />
      <Attack />
      <Order />
   </div>
</template>