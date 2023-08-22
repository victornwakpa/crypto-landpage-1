<script setup>
    import { ref } from 'vue';

    const c = [
    {
        "img" : "./src/assets/images/1.svg",
        "title": "Trade Desk",
        "desc": "Invest in crypto anytime, anywhere with our safe, secure, and easy to use online platform",
        "button" : "Get started" 
    },
    {
        "img" : "./src/assets/images/2.svg",
        "title": "CoinFlip ATMs",
        "desc": "We have thousands of ATMs located across the U.S. where you can easily convert cash to crypto",
        "button" : "Find an ATM" 
    },
    {
        "img"  : "./src/assets/images/3.svg",
        "title": "CoinFlip Wallet",
        "desc": "Store your growing investments in our non-custodial wallet that gives you access to a DeFi services",
        "button" : "Download the App" 
    }
    ];

    const cards = ref(c);
</script>

<template>
    <!-- CARD SECTION ==================== -->
    <div class="h-screen-calc grid place-content-center grid-cols-3 gap-5">
        <div v-for="card in cards" class="grid">
          <!-- FIRST CARD -->
          <div class="card-color p-6 rounded-3xl max-w-sm">
            <img class="mx-auto" :src="card.img" alt="">
            <div class="text-center flex flex-col items-center">
              <div class="mt-5 text-3xl font-extrabold ">{{card.title}}</div>
              <p class="mt-5 text-gray-400 text-lg">{{ card.desc }}</p>
              <button class=" mt-5 flex bg-slate-600 px-5 py-3 rounded-lg">
                <span class="block">{{ card.button }}</span>
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
</template>