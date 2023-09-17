<script setup>
</script>

<template>
  <div class="h-screen bg-[#FFFCF2] flex justify-center items-center gap-5">
    <div>
      <h1 class="text-6xl text-[#403D39] gothic">
        Discover Incredible <br> Products
      </h1>
      <div class="flex gap-3 martian mt-4">
        <button class="p-2 pl-4 pr-4 bg-[#403D39] rounded-3xl text-[#FFFCF2]">Shop Now</button>
        <button class="p-2 pl-4 pr-4 bg-black rounded-3xl text-[#CCC5B9]">Get Inspired</button>
      </div>
    </div>
    <img width="802" src="./images/variant1.png" alt="Produtos e Geometrias"/>
  </div>
  <div style="height: 600px" class="bg-[#CCC5B9] flex justify-center items-center relative">
    <div class="flex-col gap-5">
      <h1 class=" text-5xl text-[#252422] gothic">
        Unleash Your Inner Shopaholic
      </h1>
      <p style="width: 600px" class="pt-10 text-3xl text-[#252422] martian">
        Welcome to the best products of today! Our curated selection delivers satisfaction like no other. Stay ahead of
        the trends and experience a shopping spree that will leave you craving for more.
      </p>
    </div>
    <img class="rotate-[135deg] ml-[-300px] mt-[-75px]" width="800" src="./images/variant2.png" alt="Hiperbole Vazia"/>
  </div>
  <div style="height: 700px" class="bg-[#CCC5B9] flex justify-center gap-5 items-center relative">
    <div style="height: 400px; width: 400px"
         class="bg-[#C1B9AA] rounded-tl-3xl rounded-tr-[300px] rounded-br-[300px] rounded-bl-[300px] flex items-center justify-center flex-col">
      <h2 class="text-[#252422] text-5xl gothic">100+</h2>
      <p class="text-[#252422] text-2xl martian">Handpicked Items</p>
    </div>
    <div style="height: 400px; width: 400px"
         class="bg-[#C1B9AA] rounded-tl-3xl rounded-tr-3xl rounded-br-3xl rounded-bl-3xl flex items-center justify-center flex-col">
      <h2 class="text-[#252422] text-5xl gothic">5,000</h2>
      <p class="text-[#252422] text-2xl martian">Happy Customers</p>
    </div>
    <div style="height: 400px; width: 400px"
         class="bg-[#C1B9AA] rounded-tl-[300px] rounded-tr-3xl rounded-br-3xl rounded-bl-3xl flex items-center justify-center flex-col">
      <h2 class="text-[#252422] text-5xl gothic">10</h2>
      <p class="text-[#252422] text-2xl martian">Years Sparkling</p>
    </div>
  </div>
  <div class="bg-[#CCC5B9] flex flex-col justify-center items-center pb-20">
    <div style="width: 1200px">
      <h2 class="text-6xl text-[#403D39] mb-20 gothic">Top Trendy Picks</h2>
    </div>
      <div class="flex justify-center items-center gap-5 mb-5">
        <img style="width: 20%;opacity: 0.7" src="./images/Image@2x-1.png" alt="Produto 1"/>
        <img style="width: 20%;opacity: 0.7" src="./images/Image@2x-2.png" alt="Produto 1"/>
        <img style="width: 20%;opacity: 0.6" src="./images/Image@2x-3.png" alt="Produto 1"/>
      </div>
      <div class="flex justify-center items-center gap-5 relative">
        <img style="width: 20%; opacity: 0.7" src="./images/Image@2x-4.png" alt="Produto 1"/>
        <img  style="width: 20%; opacity: 0.7" src="./images/Image@2x-5.png" alt="Produto 1"/>
        <img style="width: 20%; opacity: 0.7" src="./images/Image@2x-6.png" alt="Produto 1"/>
      </div>
  </div>
  <div class="bg-[#CCC5B9] flex justify-center items-center">
    <div class="h-[800px] relative">
      <img class="rotate-[135deg] relative mt-[250px]" width="600" src="./images/variant2.png" alt="Hiperbole Vazia"/>
      <img class="rotate-[50deg]  relative mt-[-280px]" width="600" src="./images/variant2.png" alt="Hiperbole Vazia"/>
    </div>
    <div style="width: 600px" class="flex flex-col items-center justify-center">
      <h2 class="text-black text-5xl gothic mb-5">Ready, Set, Shop!</h2>
      <p class="text-black text-2xl martian text-center mb-5">Embark on a retail journey designed to dazzle and inspire. Your shopping cart is waiting – let’s fill it with amazing products!</p>
      <button class="p-2 pl-4 pr-4 bg-[#252422] rounded-md text-white martian">Explore now</button>
    </div>
   </div>
  <div class="bg-[#CCC5B9] flex items-center martian">
    <div class="pl-60 gap-5 flex flex-col">
      <h2>Support</h2>
      <h2>Faq</h2>
      <h2>Returns</h2>
      <h2>Shipping</h2>
    </div>
    <div class="pl-60 gap-5 flex flex-col">
      <h2>Explore</h2>
      <h2>New Arrivals</h2>
      <h2>Best Sellers</h2>
      <h2>Sale</h2>
    </div>
    <div class="pl-60 gap-5 flex flex-col">
      <h2>Company</h2>
      <h2>About Us</h2>
      <h2>Contact Us</h2>
      <h2>Careers</h2>
    </div>
  </div>
  <div class="bg-[#CCC5B9] flex items-center justify-between martian pt-20 pb-32">
    <div class="pl-60 gap-5 flex flex-col">
      <h2>2023 Best Products Today</h2>
    </div>
    <div class="pr-60 flex">
      <img  src="./images/twitter.svg" alt="twitter"/>
      <img  src="./images/instagram.svg" alt="instagram"/>
    </div>
  </div>


</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=League+Gothic&family=Raleway:wght@500&display=swap');
@import url('https://fonts.googleapis.com/css2?family=League+Gothic&family=Martian+Mono&family=Raleway:wght@500&display=swap');

.gothic {
  font-family: 'League Gothic', sans-serif;
}

.martian {
  font-family: 'Martian Mono', monospace;
}

</style>