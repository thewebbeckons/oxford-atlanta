<template>
  <div class="relative bg-dark">
    <div class="absolute inset-0">
      <img src="~/assets/atlanta-skyline-lg.jpg" alt="Atlanta"
      class="h-full w-full absolute object-cover opacity-[25%]">
      <img src="~/assets/gradient.jpg" alt=""
      class="h-full w-full absolute object-cover grayscale opacity-[10%]">
    </div>
    <MainNav />
    <HeroSection />
  </div>
  <IntroSection />
  <div class="space-y-12 lg:space-y-16">
    <SectionsLocation />
    <SectionsSchedule />
    <SectionsAttractions />
  </div>
</template>

<style>
@import url('http://fonts.cdnfonts.com/css/neue-haas-grotesk-display-pro');
h1 {
  font-family: 'Neue Haas Grotesk Display Pro', sans-serif;
  font-weight: 600;
}
html {
  scroll-behavior: smooth;
}
.bg-dark {
    background-color: #35495a!important;
}
</style>
                
