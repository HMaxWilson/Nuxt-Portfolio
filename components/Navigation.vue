<template>
    <nav class="items-center bg-white shadow-sm flex text-xl h-auto justify-between left-0 py-7 px-8 lg:py-6 lg:pl-12 lg:pr-10 fixed top-0 w-full z-40">
        <h3 class="logo font-bold text-xl text-[#2d2e32] cursor-pointer">HMaxWilson.dev</h3>

        <ul class="hidden lg:flex gap-4">
            <li class="text-[#2d2e32] font-semibold"><a href="#home">Home</a></li>
<!--            <li class="text-[#2d2e32] font-semibold"><a href="#about">About</a></li>-->
            <li class="text-[#2d2e32] font-semibold"><a href="#portfolio">Portfolio</a></li>
            <li class="text-[#2d2e32] font-semibold"><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <div class="flex lg:hidden mobile-nav closed-menu items-center bg-white h-screen justify-center left-[-100%] fixed text-center top-0 w-full z-50">
        <span class="cursor-pointer text-2xl absolute right-8 top-4">
            <FontAwesomeIcon class="fa-solid fa-xmark" />
        </span>
        <ul class="flex flex-col text-6xl gap-20">
            <li><a class="text-black font-normal" href="#home">Home</a></li>
<!--            <li><a class="text-black font-normal" href="#about">About</a></li>-->
            <li><a class="text-black font-normal" href="#portfolio">Portfolio</a></li>
            <li><a class="text-black font-normal" href="#contact">Contact</a></li>
        </ul>
    </div>
</template>

<script setup lang="ts">
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";
</script>