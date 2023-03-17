<template>
    <section id="home" class="hero bg-[#f9f9f9] flex flex-col h-auto py-24 lg:py-0 lg:h-screen relative w-full">
        <div class="container mx-auto max-w-[107rem] px-4 lg:px-16">
            <div class="content items-center flex flex-col lg:flex-row gap-6 lg:gap-20 h-auto lg:h-[50rem] text-center lg:text-left justify-center relative">
                <div class="hero-main items-center flex flex-col lg:flex-row gap-6 lg:gap-20 justify-center text-center lg:text-left relative">
                    <div class="hero-img h-[14rem] w-[14rem] sm:h-[28rem] sm:w-[28rem] lg:h-[35rem] lg:w-[35rem]" />

                    <div class="hero-info flex flex-col max-w-[50rem] relative">
                        <h1 class="text-[#2d2e32] text-5xl md:text-6xl font-bold my-4">Full-Stack Web Developer</h1>
                        <p class="text-[#767676] text-lg font-normal mb-10 md:mb-0">Hi, I'm Harrison Max-Wilson. A passionate Web Developer based in Bournemouth, United Kingdom. 📍</p>
                        <span class="cursor-pointer flex gap-4 justify-center lg:justify-start mb-8 -mt-4 md:my-5">
                            <a class="text-4xl" aria-label="linkedin" target="_blank" rel="noreferrer" href="https://www.linkedin.com/in/HMaxWilson/">
                                <FontAwesomeIcon icon="fa-brands fa-linkedin" />
                            </a>
                            <a class="text-4xl" aria-label="github" target="_blank" rel="noreferrer" href="https://github.com/HMaxWilson">
                                <FontAwesomeIcon icon="fa-brands fa-github" />
                            </a>
                        </span>

                        <div class="skills w-full items-center color-[#767676] flex flex-col lg:flex-row text-2xl">
                            <p class="border-b-2 lg:border-b-0 border-r-0 lg:border-r-2 border-[#2d2e380] font-semibold lg:mr-14 pb-2 lg:pb-0 lg:pr-4 mb-6 lg:mb-0">Tech Stack</p>
                            <div class="logos">
                                <ul class="flex flex-wrap gap-6 justify-start lg:justify-center">
                                    <li class="items-center bg-white rounded-full shadow-md cursor-pointer flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/git.svg" alt="Alternate Text" />
                                    </li>
                                    <li class="items-center bg-white rounded-full shadow-md cursor-pointer flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/html.svg" alt="Alternate Text" />
                                    </li>
                                    <li class="items-center bg-white rounded-full shadow-md cursor-pointer flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/css3.svg" alt="Alternate Text" />
                                    </li>
                                    <li class="items-center bg-white rounded-full shadow-md cursor-pointer flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/javascript.svg" alt="Alternate Text" />
                                    </li>
                                    <li class="items-center bg-white rounded-full shadow-md cursor-pointer flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/vuejs.svg" alt="Alternate Text" />
                                    </li>
                                    <li class="items-center bg-white rounded-full shadow-md cursor-pointer flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/nuxtjs.svg" alt="Alternate Text" />
                                    </li>
                                    <li class="items-center bg-white rounded-full shadow-md cursor-pointer flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/tailwind.svg" alt="Alternate Text" />
                                    </li>
                                    <li class="items-center bg-white rounded-full shadow-md cursor-pointer flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/php.svg" alt="Alternate Text" />
                                    </li>
                                    <li class="items-center bg-white rounded-full shadow-md cursor-pointer flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/laravel.svg" alt="Alternate Text" />
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup lang="ts">
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";
</script>