<script setup>
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

      <!-- CARD SECTION ==================== -->
      <div class="h-screen-calc grid place-content-center">
        <div class="grid grid-cols-3 gap-5">
          <!-- FIRST CARD -->
          <div class="card-color p-6 rounded-3xl max-w-sm">
            <img class="mx-auto" src="./assets/images/1.svg" alt="">
            <div class="text-center flex flex-col items-center">
              <div class="mt-5 text-3xl font-extrabold ">Trade Desk</div>
              <p class="mt-5 text-gray-400 text-lg">Invest in crypto anytime, anywhere with our safe, secure, and easy to use online platform</p>
              <button class=" mt-5 flex bg-slate-600 px-5 py-3 rounded-lg">
                <span class="block">Get Started</span>
                <div class="block">
                  <svg class="fill-white h-5 w-5">
                    <path d="M16.1716 10.9999L10.8076 5.63589L12.2218 4.22168L20 11.9999L12.2218 19.778L10.8076 18.3638L16.1716 12.9999H4V10.9999H16.1716Z"></path>
                  </svg>
                </div>
              </button>
            </div>
          </div>

          <!-- SECOND CARD -->
          <div class="card-color p-6 rounded-3xl max-w-md">
            <img class="mx-auto" src="./assets/images/2.svg" alt="">
            <div class="text-center flex flex-col items-center">
              <div class="mt-5 text-3xl font-extrabold ">CoinFlip ATMs</div>
              <p class="mt-5 text-gray-400 text-lg">We have thousands of ATMs located across the U.S. where you can easily convert cash to crypto</p>
              <button class=" mt-5 flex bg-slate-600 px-5 py-3 rounded-lg">
                <span class="block">Find an ATM</span>
                <div class="block">
                  <svg class="fill-white h-5 w-5">
                    <path d="M16.1716 10.9999L10.8076 5.63589L12.2218 4.22168L20 11.9999L12.2218 19.778L10.8076 18.3638L16.1716 12.9999H4V10.9999H16.1716Z"></path>
                  </svg>
                </div>
              </button>
            </div>
          </div>

          <!-- THIRD CARD -->
          <div class="card-color p-6 rounded-3xl max-w-md">
            <img class="mx-auto" src="./assets/images/3.svg" alt="">
            <div class="text-center flex flex-col items-center">
              <div class="mt-5 text-3xl font-extrabold ">CoinFlip Wallet</div>
              <p class="mt-5 text-gray-400 text-lg">Store your growing investments in our non-custodial wallet that gives you access to a DeFi services</p>
              <button class=" mt-5 flex bg-slate-600 px-5 py-3 rounded-lg">
                <span class="block">Download the App</span>
                <div class="block">
                  <svg class="fill-white h-5 w-5">
                    <path d="M16.1716 10.9999L10.8076 5.63589L12.2218 4.22168L20 11.9999L12.2218 19.778L10.8076 18.3638L16.1716 12.9999H4V10.9999H16.1716Z"></path>
                  </svg>
                </div>
              </button>
            </div>
          </div>
        </div>
      </div>

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
      <div>
        <h3>
          Buy and sell with the lowest fees in the industry
        </h3>
        <p>
          Buy and sell 150+ cryptocurrencies with 20+ fiat currencies using bank transfers or your credit/debit card.
        </p>
        <button class=" mt-5 flex bg-slate-600 px-5 py-3 rounded-lg">
          <span class="block">Get Started</span>
          <div class="block">
            <svg class="fill-white h-5 w-5">
              <path d="M16.1716 10.9999L10.8076 5.63589L12.2218 4.22168L20 11.9999L12.2218 19.778L10.8076 18.3638L16.1716 12.9999H4V10.9999H16.1716Z"></path>
            </svg>
          </div>
        </button>
      </div>

    </div>
    
  </main>
</template>

<style scoped>

</style>
