<template>
    <nav class="items-center bg-white shadow-sm flex text-xl h-auto justify-between left-0 py-7 px-8 lg:py-6 lg:pl-12 lg:pr-10 fixed top-0 w-full z-40">
        <h3 class="logo font-bold text-xl text-[#2d2e32] cursor-pointer">HMaxWilson.dev</h3>

        <ul class="hidden lg:flex gap-4">
            <li class="text-[#2d2e32] font-semibold"><a href="#home">Home</a></li>
            <li class="text-[#2d2e32] font-semibold"><a href="#portfolio">Portfolio</a></li>
            <li class="text-[#2d2e32] font-semibold"><a href="#contact">Contact</a></li>
        </ul>

        <ul class="flex lg:hidden gap-4">
            <li class="text-[#2d2e32] font-semibold">
                <span class="cursor-pointer text-2xl">
                    <FontAwesomeIcon @click="toggleMobileMenu" icon="fa-solid fa-bars-staggered" />
                </span>
            </li>
        </ul>
    </nav>

    <div class="flex lg:hidden mobile-nav items-center bg-white h-screen justify-center fixed text-center top-0 w-full z-50 ease-in-out duration-500"
         :class="{ '-translate-x-full' : mobileMenuClosed }">
        <span class="cursor-pointer text-black text-2xl absolute right-8 top-4">
            <FontAwesomeIcon @click="toggleMobileMenu" icon="fa-solid fa-xmark" />
        </span>
        <ul class="flex flex-col text-6xl gap-20">
            <li><a class="text-black font-normal" @click="toggleMobileMenu" href="#home">Home</a></li>
            <li><a class="text-black font-normal" @click="toggleMobileMenu" href="#portfolio">Portfolio</a></li>
            <li><a class="text-black font-normal" @click="toggleMobileMenu" href="#contact">Contact</a></li>
        </ul>
    </div>
</template>

<script setup lang="ts">
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";
import { ref } from "vue";

const mobileMenuClosed = ref(true);
const toggleMobileMenu = () => {
  mobileMenuClosed.value = !mobileMenuClosed.value;
}
</script>