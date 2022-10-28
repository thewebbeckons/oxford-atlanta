<template>
  <header class="max-w-5xl mx-auto relative pt-4 lg:pt-8 flex items-center justify-between px-4 lg:px-0">
    <div class="w-[150px] bg-[#11252B] p-4 flex items-center justify-center">
      <Logo />
    </div>
    <MobileMenu />
    <div class="hidden w-full md:block md:w-auto" id="navbar-default">
      <ul class="text-white text-sm font-medium lg:text-base lg:font-semibold flex items-center space-x-4 lg:space-x-8">
        <li>
          <a href="#schedule">
            Schedule
          </a>
        </li>
        <li>
          <a href="#locations">
            Locations
          </a>
        </li>
        <li>
          <a href="#attractions">
            Attractions
          </a>
        </li>
      </ul>
    </div>
  </header>
</template>
<script setup>
  import { Menu, MenuButton, MenuItems, MenuItem } from '@headlessui/vue'
</script>