<template>
  <div id="attractions" class="bg-[#e4dfdc]">
    <div class="max-w-4xl mx-auto px-4 py-8">
      <h2 class="text-slate-800 text-4xl lg:text-5xl font-bold py-4">
        Attractions
      </h2>
      <div class="pb-4">
        <!-- <h2 class="text-sm font-semibold uppercase tracking-wider text-blue-600">
            GAMC 2022
        </h2> -->
        <!-- <p class="mt-2 text-slate-800 text-2xl font-normal ">
          
        </p> -->
        <p class="mt-6 text-base font-light lg:text-lg text-slate-800">
          Welcome to Atlanta! With a population 6.1 million people in the greater Atlanta area, the city is the 8th largest metropolitan area in the US. 
        </p>
        <p class="mt-6 text-base font-light lg:text-lg text-slate-800">
          A few suggested local attractions for team members looking to explore the area:
        </p>
      </div>
      <div class="grid grid-cols-1 gap-x-6 gap-y-8 sm:grid-cols-2 lg:gap-x-6 lg:gap-y-1 my-6">
        <div class="">
          <img src="~/assets/park.jpeg" alt="Centennial Olympic Park" class="mb-4">
          <a class="font-bold text-lg text-slate-800 hover:underline cursor-pointer"
          herf="https://www.gwcca.org/centennial-olympic-park">
            Centennial Olympic Park
          </a>
          <p class="text-slate-800 font-light py-4">
            The world’s gathering place during the 1996 Centennial Olympic Games 
          </p>
          <a href="https://www.google.com/maps/dir//Centennial+Olympic+Park+265+Park+Ave+W+NW+Atlanta,+GA+30313+United+States/@33.7618207,-84.3945295,16z/data=!4m5!4m4!1m0!1m2!1m1!1s0x88f5047fa6211621:0x5353cbfc3e0d2d5b" 
          class="text-base font-semibold text-sky-800 flex">
            Directions
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
              <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3" />
            </svg>
          </a>
        </div>
        <div class="">
          <img src="~/assets/worldcoca-cola.jpeg" alt="World of Coca-Cola" class="mb-4">
          <a class="font-bold text-lg text-slate-800 hover:underline cursor-pointer"
          href="https://www.worldofcoca-cola.com/">
            World of Coca-Cola
          </a>
          <p class="text-slate-800 font-light py-4">
            Where the famous soft drink’s story is told through fascinating exhibits, classic ads and an imaginative replica of the bottling process
          </p>
          <a href="https://www.google.com/maps/dir//World+of+Coca-Cola,+Baker+Street+Northwest,+Atlanta,+GA,+USA/@33.7619397,-84.3972156,17.49z/data=!4m8!4m7!1m0!1m5!1m1!1s0x88f5047eecc828f3:0x4401b29a011fa7c9!2m2!1d-84.392436!2d33.7625564" 
          class="text-base font-semibold text-sky-800 flex">
            Directions
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
              <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3" />
            </svg>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>