<script setup>
</script>

<template>
  <main class="bg-color min-h-full">
    <div class="px-8 py-8 w-full text-white min-h-screen">
      <!-- NAVIGATION BAR ======================= -->
      <div class="flex justify-between items-center">
        <div>
          <span class="uppercase">coinflip</span>
        </div>
        <div>
          <ul class="flex">
            <li class="px-2">Bull/Sell</li>
            <li class="px-2">Grow</li>
            <li class="px-2">Market</li>
            <li class="px-2">Business</li>
            <li class="px-2">Support</li>
          </ul>
        </div>
        <div class="grid gap-1 grid-cols-2">
          <button class="px-5 py-3 bg-slate-400 rounded-xl">Sign in</button>
          <button class="px-5 py-3 bg-slate-400 rounded-xl">Sign up</button>
        </div>
      </div>

      <!-- HERO SECTION ============================ -->
      <div class="flex justify-center flex-col items-center h-screen-calc">
        <h2 class="text-7xl hero-title">
          <span class="block mb-3">We make crypto</span>
          <span class="block mb-3">clear and simple</span>
        </h2>
        <p class="mt-3 max-w-xl text-center">Buy, sell, and grow your crypto with CoinFlip, the platform dedicated to every trader at every level.</p>
        <button class="mt-5 py-5 px-3 bg-purple-700">Get Started</button>
      </div>
    </div>
    
  </main>
</template>

<style scoped>

</style>
