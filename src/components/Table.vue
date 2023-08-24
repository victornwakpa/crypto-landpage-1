<script setup>

  const tableRow = [
    {
      coin: "Bitcoin",
      abbr: "BTC",
      price: "56,290.30",
      rise: "+1.68%",
      image: "graph-1.svg"
    },
    {
      coin: "Ethereum",
      abbr: "ETH",
      price: "4,284.81",
      rise: "+4.36%",
      image: "graph-2.svg"
    },
    {
      coin: "Cardano",
      abbr: "ADA",
      price: "1.88",
      rise: "+3.43%",
      image: "graph-3.svg"
    },
    {
      coin: "Wax",
      abbr: "WAXP",
      price: "0.97",
      rise: "-2.62%",
      image: "graph-4.svg"
    },
    {
      coin: "Polkadot",
      abbr: "DOT",
      price: "42.22",
      rise: "+7.56%",
      image: "graph-5.svg"
    }
  ]
</script>


<template>
    <div class="">
        <table class="border-2 border-collapse rounded-xl overflow-hidden table-color">
          <tbody class="border-custom">
            <tr v-for="row in tableRow" class="">
              <th class="font-bold text-xl">{{ row.coin }}</th>
              <td class="p-3 text-purple-500 font-bold text-lg">{{ row.abbr }}</td>
              <td class="p-3 font-bold text-xl">${{ row.price }}</td>
              <td class="p-3 font-bold text-green-500">{{ row.rise }}</td>
              <td class="p-3">
                <img :src="`./src/assets/images/${row.image}`" alt="">
              </td>
              <td class="p-3">
                <button class="flex rounded-lg">
                <span class="block font-bold">Trade Now</span>
                <div class="w-3 h-3">
                  <svg class="fill-white">
                    <path d="M16.1716 10.9999L10.8076 5.63589L12.2218 4.22168L20 11.9999L12.2218 19.778L10.8076 18.3638L16.1716 12.9999H4V10.9999H16.1716Z"></path>
                  </svg>
                </div>
              </button>
              </td>
            </tr>

            
          </tbody>
        </table>
      </div>
</template>