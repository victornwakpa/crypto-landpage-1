<script setup>
  import Card from "./components/Card.vue";
  import Table from "./components/Table.vue";
  import Footer from "./components/Footer.vue";
</script>

<template>
  <main class="bg-color min-h-full max-w-full">
    <div class="px-20 py-8 w-full text-white min-h-screen">
      <!-- NAVIGATION BAR ======================= -->
      <div class="flex justify-between items-center">
        <div>
          <span class="uppercase font-extrabold tracking-wider text-xl">coinflip</span>
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
        <div class="grid gap-2 grid-cols-2">
          <button class="px-5 py-3 bg-slate-400 rounded-xl font-bold">Sign in</button>
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
        <button class="mt-5 px-5 py-3 bg-purple-700 rounded-xl font-semibold">Get Started</button>
      </div>

      <Card />

      <!-- CLICK CATCH ============================= -->
      <div class="">
        <!-- FIRST SECTION ========================= -->
        <div class="text-center mx-auto max-w-3xl mb-48 mt-44 ">
          <h3 class="font-extrabold text-5xl py-3">
            A crypto investment platform that invests in you 
          </h3>
          <p class="mt-5 max-w-xl mx-auto py-3">
            We invest more resources than any other platrom in making sure great support from real people is a click away, whenever you need it.
          </p>
          <button class="mt-5 bg-slate-500 py-3 px-5 rounded-xl">
            Get Started
          </button>
        </div>

        <!-- SECOND SECTION ========================= -->
        <div class="flex items-center justify-center">
          <div class="flex-1 grid place-content-center">
            <img class="w-52 text-center" src="./assets/images/icons.svg" alt="">
          </div>
          <div class="flex-1 text-left px-12 py-6">
            <h3 class="text-4xl font-extrabold max-w-sm p-2">
              24/7 access to full service customer support
            </h3>
            <p class="mt-3 p-2 text-sm max-w-md">
              We invest more resources than any other platform in making sure great support from real people is a click away, whenever you need it.
            </p>
            <button class="m-2 rounded-md p-2 border-2 border-white">Get Started</button>
          </div>
        </div>

      </div>

      <!--  BUY AND SELL SECTION ================= -->
      <div class="mt-24">
        <div class="text-center px-12 py-6">
            <h3 class="text-4xl font-extrabold max-w-lg mx-auto p-2">
              24/7 access to full service customer support
            </h3>
            <p class="mt-3 p-2 mx-auto text-sm max-w-lg">
              We invest more resources than any other platform in making sure great support from real people is a click away, whenever you need it.
            </p>
            <button class="m-2 rounded-md p-2 border-2 border-white">Get Started</button>
          </div>
      </div>

      <Table />

      <div class="h-screen-calc grid mt-24">
        <div class="text-left px-12 py-6">
          <h3 class="text-4xl font-extrabold max-w-sm p-2">
            24/7 access to full service customer support
          </h3>
          <p class="mt-3 p-2 text-sm max-w-md">
            We invest more resources than any other platform in making sure great support from real people is a click away, whenever you need it.
          </p>
          <button class="m-2 rounded-md p-2 border-2 border-white">Get Started</button>
        </div>
      </div>

      <!-- NEWLETTER =================== -->
      <div class="grid place-content-center">
        <h4>Recieve transmission</h4>
        <p>
          <span>Unsubscribe at any time. </span>
          <span>Privacy policy.</span>
          <span class="inline-block">
            <svg class="fill-white h-5 w-5">
              <path d="M16.1716 10.9999L10.8076 5.63589L12.2218 4.22168L20 11.9999L12.2218 19.778L10.8076 18.3638L16.1716 12.9999H4V10.9999H16.1716Z"></path>
            </svg>
          </span>
        </p>
        <form action="">
          <input type="text" placeholder="Email Address">
        </form>
      </div>

      <!-- FOOTER SECTION -->
      <Footer />

    </div>
    
  </main>
</template>

<style scoped>

</style>
