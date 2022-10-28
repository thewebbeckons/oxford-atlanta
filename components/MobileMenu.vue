<template>
   <Menu as="div" class="relative inline-block text-left sm:hidden z-10">
      <div>
        <MenuButton
          class="inline-flex w-full justify-center rounded-md px-2 py-2 text-sm font-medium text-white hover:bg-opacity-30 focus:outline-none focus-visible:ring-2 focus-visible:ring-white focus-visible:ring-opacity-75"
        >
        <svg class="w-6 h-6" aria-hidden="true" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
        </MenuButton>
      </div>

      <transition
        enter-active-class="transition duration-100 ease-out"
        enter-from-class="transform scale-95 opacity-0"
        enter-to-class="transform scale-100 opacity-100"
        leave-active-class="transition duration-75 ease-in"
        leave-from-class="transform scale-100 opacity-100"
        leave-to-class="transform scale-95 opacity-0"
      >
        <MenuItems
          class="absolute right-0 mt-2 w-56 origin-top-right divide-y divide-gray-100 rounded-md bg-slate-800 shadow-lg ring-1 ring-black ring-opacity-5 focus:outline-none"
        >
          <div class="px-1 py-1">
            <MenuItem>
              <a
                class="group flex w-full items-center rounded-md px-2 py-2 text-sm text-white"
                href="#schedule"
              >
                Schedule
              </a>
            </MenuItem>
            <MenuItem>
              <a
                class="group flex w-full items-center rounded-md px-2 py-2 text-sm text-white"
                href="#locations"
              >
                Locations
              </a>
            </MenuItem>
            <MenuItem>
              <a
                class="group flex w-full items-center rounded-md px-2 py-2 text-sm text-white"
                href="#attractions"
              >
                Attractions
              </a>
            </MenuItem>
          </div>
        </MenuItems>
      </transition>
    </Menu>
</template>

<script setup>
import { Menu, MenuButton, MenuItems, MenuItem } from '@headlessui/vue'
</script>