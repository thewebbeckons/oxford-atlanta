<template>
  <div v-if="talk.type == 'talk'">
    <div class="w-full flex flex-col group cursor-pointer">
      <div class="group-hover:bg-gradient-to-r from-slate-800 to-slate-700 p-1 rounded-lg">
        <div class="block md:flex items-center lg:items-start py-4 lg:py-8 px-4 lg:px-8 rounded-lg hover:shadow-md bg-dark">
          <div class="mb-4 md:mb-0">
            <h3 class="text-sm lg:text-xl font-semibold text-white leading-tight">
              {{ talk.startTime }} - {{ talk.endTime }}
            </h3>
          </div> 
          <div class="flex flex-1 md:ml-16">
            <div class="flex flex-col md:flex-row w-full">
              <div class="flex items-center lg:items-start w-full">
                <div class="flex-1 md:ml-4 text-left w-full">
                  <div class="w-full">
                    
                    <h3 class="text-white text-base lg:text-xl font-semibold leading-tight">
                      {{ talk.title }}
                    </h3>
                    <p class="text-[#84aadd] leading-none text-sm lg:text-lg">
                      {{ talk.people }}
                    </p>
                  </div>
                </div>
              </div> 
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div v-else>
    <div class="w-full flex flex-col group cursor-pointer">
      <div class="italic p-1">
        <div class="block md:flex items-center lg:items-start py-2 lg:py-8 px-4 lg:px-8 rounded-lg hover:shadow-md bg-gray-200">
          <div class="mb-2 md:mb-0">
            <h3 class="text-sm lg:text-xl font-semibold text-slate-800 leading-tight">
              {{ talk.startTime }} - {{ talk.endTime }}
            </h3>
          </div> 
          <div class="flex flex-1 md:ml-16">
            <div class="flex flex-col md:flex-row w-full">
              <div class="flex items-center lg:items-start w-full">
                <div class="flex-1 md:ml-4 text-left w-full">
                  <div class="w-full">
                    <h3 class="text-slate-800 text-base lg:text-xl font-semibold leading-tight">
                      {{ talk.title }}
                    </h3>
                  </div>
                </div>
              </div> 
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- <div v-else>
    <div class="px-1">
      <div class="p-8 rounded-lg">
        <h3 class="text-slate-800 text-sm lg:text-xl font-semibold leading-none">
          {{ talk.title }}
        </h3>
      </div>
    </div>
  </div> -->
</template>

<script setup>
  const props = defineProps(['talk'])
</script>

<style>

</style>