<script lang="ts" setup>

</script>

<template>
   <div class="container px-10 max-md:px-5 !mt-16">
      <h1 class="max-md:text-[40px]">{{ $t('Indicators') }}</h1>
      <p class="mt-8 mb-8 lg:text-2xl max-w-[800px] w-full">Интересные цифры, при помощи которых можно наглядно показать
         надёжность решения и правильность выбора</p>
      <div class="grid grid-cols-3 max-sm:grid-cols-1 gap-4 max-lg:gap-2">
         <div class="p-6 rounded-tr-2xl rounded-bl-2xl border-2 border-primary-200">
            <h1 class="mb-2 font-Manrope-800 max-md:text-[40px] leading-[56px] text-primary"> 4 141</h1>
            <p class="font-Manrope-700 text-xl max-md:text-5">{{ $t('database') }}
            </p>
         </div>
         <div class="p-6 rounded-tr-2xl rounded-bl-2xl border-2 border-primary-200">
            <h1 class="mb-2 font-Manrope-800 max-md:text-[40px] leading-[56px] text-primary"> 55 142</h1>
            <p class="font-Manrope-700 text-xl max-md:text-5">{{ $t('operations') }}
            </p>
         </div>
         <div class="p-6 rounded-tr-2xl rounded-bl-2xl border-2 border-primary-200">
            <h1 class="mb-2 font-Manrope-800 max-md:text-[40px] leading-[56px] text-primary"> 878 924</h1>
            <p class="font-Manrope-700 text-xl max-md:text-5">{{ $t('identifications') }}
            </p>
         </div>
      </div>
   </div>
</template>