<template>
  <div class="mx-4 my-4 sm:mx-8 sm:my-8 lg:mx-20 lg:my-20 container flex-col items-center gap-6 flex w-full lg:w-[80%]">
    <!-- Product Info -->
    <div class="flex-col justify-start items-start gap-2 flex w-full lg:w-auto">
      <div class="text-[#9c9c9c] text-xs sm:text-sm font-normal font-['Montserrat'] leading-normal">Ref.: 00000000000</div>
      <div class="w-full lg:w-[467px] text-black text-[20px] sm:text-[24px] lg:text-[32px] font-bold font-['Montserrat']">
        Óculos de sol | Dubay Emy
      </div>
      <div class="flex items-center gap-[15px]">
        <div class="text-black text-xs sm:text-sm font-normal font-['Montserrat'] leading-none tracking-tight">342 avaliações</div>
      </div>
    </div>

    <!-- Main Image -->
    <img class="w-full h-auto lg:w-[473px] lg:h-[375px] object-cover" src="../../assets/images/product/Rectangle63.svg" alt="Product Image"/>

    <!-- Thumbnail Images -->
    <div class="flex justify-start items-start gap-4 overflow-x-auto">
      <img class="w-[60px] h-[60px] sm:w-[73px] sm:h-[72px]" src="../../assets/images/product/Rectangle64.svg" alt="Thumbnail" />
      <img class="w-[60px] h-[60px] sm:w-[73px] sm:h-[72px]" src="../../assets/images/product/Rectangle65.svg" alt="Thumbnail" />
      <img class="w-[60px] h-[60px] sm:w-[73px] sm:h-[71px]" src="../../assets/images/product/Rectangle66.svg" alt="Thumbnail" />
      <img class="w-[60px] h-[60px] sm:w-[72px] sm:h-[71px]" src="../../assets/images/product/Rectangle67.svg" alt="Thumbnail" />
      <img class="w-[60px] h-[60px] sm:w-[73px] sm:h-[72px]" src="../../assets/images/product/Rectangle68.svg" alt="Thumbnail" />
      <img class="w-[60px] h-[60px] sm:w-[73px] sm:h-[72px]" src="../../assets/images/product/Rectangle69.svg" alt="Thumbnail" />
    </div>

    <!-- Pricing Information -->
    <div class="flex-col justify-start items-center gap-1 flex">
      <div class="text-center text-[#9c9c9c] text-sm sm:text-base font-normal font-['Montserrat'] line-through">R$ 99,90</div>
      <div class="text-center text-black text-[28px] sm:text-[32px] lg:text-[40px] font-bold font-['Montserrat']">R$ 49,90</div>
      <div class="text-center text-[#9c9c9c] text-sm sm:text-base font-normal font-['Montserrat']">no Pix, boleto ou cartão</div>
    </div>

    <!-- Color Picker -->
    <div class="w-full sm:w-60 h-10 relative flex justify-center gap-4">
      <div class="w-10 h-10 relative">
        <div class="w-10 h-10 bg-white rounded-full border border-[#d6d6d6]"></div>
        <div class="w-8 h-8 bg-[#7b5823] rounded-full absolute top-1 left-1"></div>
      </div>
      <div class="w-10 h-10 relative">
        <div class="w-10 h-10 bg-white rounded-full border border-[#d6d6d6]"></div>
        <div class="w-8 h-8 bg-[#512f2f] rounded-full absolute top-1 left-1"></div>
      </div>
      <div class="w-10 h-10 relative">
        <div class="w-10 h-10 bg-white rounded-full border border-[#d6d6d6]"></div>
        <div class="w-8 h-8 bg-[#2f381b] rounded-full absolute top-1 left-1"></div>
      </div>
      <div class="w-10 h-10 relative">
        <div class="w-10 h-10 bg-white rounded-full border border-[#d6d6d6]"></div>
        <div class="w-8 h-8 bg-[#1d1d1b] rounded-full absolute top-1 left-1"></div>
      </div>
      <div class="w-10 h-10 relative">
        <div class="w-10 h-10 bg-white rounded-full border border-[#d6d6d6]"></div>
        <div class="w-8 h-8 bg-[#c9c9c9] rounded-full absolute top-1 left-1"></div>
      </div>
    </div>

    <!-- Quantity Selector -->
    <div class="flex justify-start items-center gap-2">
      <div class="text-[#414042] text-sm font-normal font-['Montserrat']">Quantidade:</div>
      <div class="w-[62px] h-[50px] relative">
        <div class="w-[62px] h-[50px] border border-[#a0a0a0] rounded-[5px] flex justify-center items-center">
          <span class="text-[#7a7a7a] text-sm font-normal font-['Montserrat']">1</span>
        </div>
      </div>
    </div>

    <!-- Additional Options -->
    <div class="flex flex-wrap justify-start items-center gap-6">
      <div class="flex items-center gap-1.5">
        <div class="text-black text-sm font-bold font-['Montserrat']">Guia de Medidas</div>
      </div>
      <div class="flex items-center gap-1.5">
        <div class="text-black text-sm font-bold font-['Roboto']">Provador Virtual</div>
      </div>
      <div class="flex items-center gap-1.5">
        <div class="text-black text-sm font-bold font-['Roboto']">Medidor DNP</div>
      </div>
    </div>

    <!-- Add to Cart Button -->
    <div class="w-full lg:w-[486px] py-4 sm:py-6 bg-[#138a00] rounded-[48px] flex justify-center items-center">
      <div class="text-white text-base font-bold font-['Roboto'] uppercase">adicionar ao carrinho e escolher lentes</div>
    </div>

    <!-- Shipping Calculation -->
    <div class="w-full lg:w-[486px] h-[74px] relative">
      <div class="text-center text-black text-sm font-bold font-['Roboto']">Cálculo de frete</div>
      <div class="h-[50px] flex justify-start items-center gap-2 mt-2">
        <div class="text-[#414042] text-sm font-normal font-['Montserrat']">Digite seu CEP:</div>
        <div class="flex border border-[#a0a0a0] rounded-[5px]">
          <input class="w-[165px] h-[50px] text-center" type="text" placeholder="00000-000" />
        </div>
        <div class="w-[197px] h-[50px] py-6 bg-black rounded-[48px] flex justify-center items-center">
          <div class="text-white text-base font-bold font-['Montserrat'] uppercase">Calcular</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
</style>
