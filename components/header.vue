<template>
  <div class="container mx-auto flex justify-between items-center bg-white text-white w-[1,600px] h-[109px] border" >

      <!-- Brand/Logo -->
      <NuxtLink to="/" class="text-2xl font-bold text-black ">
        Logo
      </NuxtLink>

      <!-- Menu Items -->
      <ul class="flex space-x-6 text-black">
        <li>
          <NuxtLink to="/" class=" " active-class="text-orange-400">
            Home
          </NuxtLink>
        </li>
        <li>
          <NuxtLink to="/about" class=" " active-class="text-orange-400">
            About
          </NuxtLink>
        </li>
        <li>
          <NuxtLink to="/our-services" class=" " active-class="text-orange-400">
            Our Services
          </NuxtLink>
        </li>
        <li>
          <NuxtLink to="/liquidate" class=" " active-class="text-orange-400">
            Liquidate
          </NuxtLink>
        </li>
        <li>
          <NuxtLink to="/governance-and-responsibility" class=" " active-class="text-orange-400">
            Governance & Responsibility
          </NuxtLink>
        </li>

        <!-- HMR Group Dropdown -->
        <li class="relative group">
          <NuxtLink to="/hmr-group" class=" hover:text-orange-400" active-class="text-orange-400">
            HMR-Group
          </NuxtLink>

          <!-- Dropdown menu -->
          <ul class="absolute left-0 top-5 mt-1 hidden group-hover:block bg-white text-blue-950 shadow-lg rounded-md w-48 z-50">
            <li>
              <NuxtLink to="/hmr-group-reverse-logistics" class="block px-4 py-2  hover:bg-blue-950 hover:text-white" >
                Reverse Logistics
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/hmr-group-trading-haus" class="block px-4 py-2  hover:bg-blue-950 hover:text-white" >
                Trading Haus
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/hmr-group-auctions" class="block px-4 py-2  hover:bg-blue-950 hover:text-white" >
                Auctions
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/hmr-group-envirocycle" class="block px-4 py-2   hover:bg-blue-950 hover:text-white" >
                Envirocycle
              </NuxtLink>
            </li>
          </ul>
        </li>

        <li>
          <NuxtLink to="/" class=" " active-class="text-orange-400">
            Contact Us
          </NuxtLink>
        </li>
      </ul>

      <!-- Button -->
      <button class="custom-button text-white">
        Button
      </button>
  </div>
</template>

<script setup>

</script>

<style scoped>
.header-bg {
  background: linear-gradient(
      89.65deg,
      rgba(120, 175, 253, 0.1) 11.52%,
      #0B2B5A 146.14%
    ),
  url('~/assets/header2.png');
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 460px;
}
</style>