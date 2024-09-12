<template>
    <header class="relative w-full">
      <!-- Barra preta superior -->
      <div class="bg-black shadow-lg h-[70px] w-full"></div>
      <!-- Barra cinza inferior -->
      <div class="bg-gray-100 h-[45px] w-full"></div>
  
      <!-- Campo de busca -->
      <div class="absolute left-1/2 top-2 transform -translate-x-1/2 w-[789px] h-[51px]">
        <div class="relative h-full bg-gray-700 flex items-center">
          <div class="bg-white h-full w-[162px] flex items-center justify-center">
            <span class="text-black font-medium text-lg">Pesquisar</span>
          </div>
          <span class="text-white ml-4">Encontre o produto que está procurando...</span>
        </div>
      </div>
  
      <!-- Logo ou ícone -->
      <div class="absolute left-[199px] top-4 flex items-center">
        <div class="w-[33px] h-[33px] bg-blue-400 rounded-full flex justify-center items-center">
          <!-- Coloque aqui o conteúdo do logo/ícone -->
          <div class="w-[16px] h-[16px] bg-white"></div>
        </div>
        <span class="ml-4 text-white text-lg font-bold">Logo</span>
      </div>
  
      <!-- Menu de navegação -->
      <nav class="absolute left-[160px] top-[75px] flex space-x-10">
        <a href="#" class="text-black font-bold">Top 5 mais vendidos</a>
        <a href="#" class="text-black">Lançamentos</a>
        <a href="#" class="text-black">Óculos de sol</a>
        <a href="#" class="text-black">Óculos de grau</a>
        <a href="#" class="text-black">Lentes de contato</a>
        <a href="#" class="text-black">Lentes para óculos</a>
        <a href="#" class="text-black">Marcas</a>
      </nav>
  
      <!-- Ícones à direita -->
      <div class="absolute right-[50px] top-[23px] flex space-x-4">
        <div class="w-[24px] h-[24px] bg-white"></div>
        <div class="w-[24px] h-[24px] bg-white"></div>
        <div class="w-[24px] h-[24px] bg-white"></div>
      </div>
    </header>
  </template>
  
  
  <style scoped>
  /* Estilos adicionais, se necessário */
  </style>
  