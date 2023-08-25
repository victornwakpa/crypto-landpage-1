<script setup>
  import Card from "./components/Card.vue";
  import Table from "./components/Table.vue";
  import Footer from "./components/Footer.vue";
</script>

<template>
  <main class="bg-color min-h-full max-w-full">
    <div class="w-full text-white">
      <div class="bg-hero px-20 py-8">
        <div class="min-h-screen">
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
              <button class="px-5 py-2 rounded-xl border-2 font-bold">Sign in</button>
              <button class="px-5 py-2 button__gradient font-bold rounded-xl">Sign up</button>
            </div>
          </div>

          <!-- HERO SECTION ============================ -->
          <div class="flex justify-center flex-col items-center h-screen-calc">
            <h2 class="text-7xl hero-title">
              <span class="block mb-3">We make crypto</span>
              <span class="block mb-3">clear and simple</span>
            </h2>
            <p class="mt-3 max-w-xl text-center text-gray-400">Buy, sell, and grow your crypto with CoinFlip, the platform dedicated to every trader at every level.</p>
            <button class="mt-5 px-5 py-3 button__gradient rounded-xl font-semibold">Get Started</button>
          </div>

        </div>
        <Card />
      </div>

      <!-- CLICK CATCH ============================= -->
      <div class="relative">
        <!-- FIRST SECTION ========================= -->
        <div class="text-center mx-auto max-w-3xl mb-48 mt-44 z-1">
          <h3 class="font-extrabold text-5xl py-2 leading-custom">
            A crypto investment platform that invests in you 
          </h3>
          <p class="max-w-xl mx-auto py-3 text-gray-400">
            We invest more resources than any other platrom in making sure great support from real people is a click away, whenever you need it.
          </p>
          <button class="mt-5 button__gradient py-3 px-5 rounded-xl">
            Get Started
          </button>
        </div>

        <img class="absolute right-[0] z-0 top-[-150px]" src="./assets/images/Looper-3.svg" alt="">


        <!-- SECOND SECTION ========================= -->
        <div class="flex items-center justify-center z[1]">
          <div class="flex-1 grid place-content-center">
            <img class="w-52 text-center" src="./assets/images/icons.svg" alt="">
          </div>
          <div class="flex-1 text-left px-10 py-6">
            <h3 class="text-5xl font-extrabold p-2 leading-custom">
              24/7 access to full service customer support
            </h3>
            <p class="mt-3 mb-4 p-2 text-md text-gray-400">
              We invest more resources than any other platform in making sure great support from real people is a click away, whenever you need it.
            </p>
            <button class="m-2 rounded-md px-4 py-2 border-2 border-white">Get Started</button>
          </div>
        </div>

      </div>

      <!--  BUY AND SELL SECTION ================= -->
      <div class="mt-24">
        <div class="text-center px-12 py-6">
            <h3 class="text-5xl font-extrabold max-w-3xl leading-custom mx-auto p-2">
              Buy and sell with the lowest fees in the industry
            </h3>
            <p class="mt-3 p-2 mx-auto text-sm max-w-lg text-gray-400">
              Buy and sell 150+ cryptocurrencies with 20+ fiat currencies using bank transfers or your credit/debit card.
            </p>
            <button class="my-3 text-purple-500">
              <div class="flex">
                <span class="block font-bold">Trade Now</span>
                <div class="w-3 h-3">
                  <svg class="fill-purple-500">
                    <path d="M16.1716 10.9999L10.8076 5.63589L12.2218 4.22168L20 11.9999L12.2218 19.778L10.8076 18.3638L16.1716 12.9999H4V10.9999H16.1716Z"></path>
                  </svg>
                </div>
              </div>
            </button>
          </div>
      </div>

      <Table />

      <div class="flex items-center justify-center flex-row-reverse h-screen mt-24 px-20 py-8">
        <div class="flex-1 grid place-content-center">
          <img class="w-52 text-center" src="./assets/images/icons-2.svg" alt="">
        </div>
        <div class="flex-1 text-left px-12 py-6">
          <h3 class="text-5xl leading-custom font-extrabold max-w-lg p-2">
            Take your first step into safe, secure crypto investing
          </h3>
          <p class="mt-3 mb-4 p-2 text-md text-gray-400 leading-">
            Separated they live in Bookmarks right at the coast of the famous Semantics, large language ocean Separated they live in Bookmarks right at the coast.
          </p>
          <button class="m-2 rounded-md px-4 py-2 button__gradient font-bold">Get Started</button>
        </div>
      </div>

      <!-- NEWLETTER =================== -->
      <div class="grid my-32">
        <div class="text-sm max-w-2xl mx-auto  p-5 text-center">
          <h3 class="text-5xl font-extrabold">Recieve transmission</h3>
          <p class="my-3">
            <span class="text-gray-400">Unsubscribe at any time. </span>
            <span class="text-gray-200">Privacy policy.</span>
            <span class="inline-block ">
              <svg class="fill-gray-200 w-5 h-5">
                <path d="M16.0037 9.41421L7.39712 18.0208L5.98291 16.6066L14.5895 8H7.00373V6H18.0037V17H16.0037V9.41421Z"></path>
              </svg>
            </span>
          </p>
          <form action="">
            <input type="text" class="p-2 rounded-lg bg-transparent border-2 my-3" placeholder="Email Address">
          </form>
        </div>
      </div>

      <!-- FOOTER SECTION -->
      <Footer />

    </div>
    
  </main>
</template>

<style scoped>

</style>
