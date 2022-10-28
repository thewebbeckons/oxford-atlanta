<template>
  <div id="attractions" class="max-w-4xl mx-auto px-4">
    <h2 class="text-white text-3xl font-bold mb-4">Local Attractions</h2>
    <div class="py-4 lg:py-8 px-4 lg:px-6 rounded-lg hover:shadow-md bg-slate-900">
      <h2 class="text-sm font-semibold uppercase tracking-wider text-blue-600">
          GAMC 2022
      </h2>
      <p class="mt-2 text-white text-3xl font-bold">
        Welcome to Atlanta 🎉
      </p>
      <p class="mt-6 text-base font-light lg:text-lg text-gray-200">
        With a population 6.1 million people in the greater Atlanta area, the city is the 8th largest metropolitan area in the US. 
      </p>
      <p class="mt-6 text-base font-light lg:text-lg text-gray-200">
        A few suggested local attractions for team members looking to explore the area:
      </p>
    </div>
    <div class="grid grid-cols-1 gap-x-6 gap-y-4 sm:grid-cols-2 lg:gap-x-6 lg:gap-y-1 my-6">
      <div class="rounded-md bg-slate-900 p-6">
        <img src="~/assets/park.jpeg" alt="Centennial Olympic Park" class="rounded-md mb-4">
        <a class="font-bold text-lg text-white hover:text-blue-600 cursor-pointer"
        herf="https://www.gwcca.org/centennial-olympic-park">
          Centennial Olympic Park
        </a>
        <p class="text-white font-light py-4">
          The world’s gathering place during the 1996 Centennial Olympic Games 
        </p>
        <a href="https://www.google.com/maps/dir//Centennial+Olympic+Park+265+Park+Ave+W+NW+Atlanta,+GA+30313+United+States/@33.7618207,-84.3945295,16z/data=!4m5!4m4!1m0!1m2!1m1!1s0x88f5047fa6211621:0x5353cbfc3e0d2d5b" class="text-base font-semibold text-blue-600">Directions</a>
      </div>
      <div class="rounded-md bg-slate-900 p-6">
        <img src="~/assets/worldcoca-cola.jpeg" alt="World of Coca-Cola" class="rounded-md mb-4">
        <a class="font-bold text-lg text-white hover:text-blue-600 cursor-pointer"
        href="https://www.worldofcoca-cola.com/">
          World of Coca-Cola
        </a>
        <p class="text-white font-light py-4">
          Where the famous soft drink’s story is told through fascinating exhibits, classic ads and an imaginative replica of the bottling process
        </p>
        <a href="https://www.google.com/maps/dir//World+of+Coca-Cola,+Baker+Street+Northwest,+Atlanta,+GA,+USA/@33.7619397,-84.3972156,17.49z/data=!4m8!4m7!1m0!1m5!1m1!1s0x88f5047eecc828f3:0x4401b29a011fa7c9!2m2!1d-84.392436!2d33.7625564" class="text-base font-semibold text-blue-600">Directions</a>
      </div>
    </div>
  </div>
</template>