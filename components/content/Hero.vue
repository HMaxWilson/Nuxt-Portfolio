<template>
    <section id="home" class="hero bg-[#f9f9f9] py-24">
        <div class="container mx-auto max-w-[68rem] px-4">
            <div class="content flex h-[50rem] justify-center">
                <div class="hero-main items-center flex flex-col lg:flex-row gap-6 text-center lg:text-left">
                    <div class="hero-img h-[14rem] w-[14rem] sm:h-[28rem] sm:w-[28rem] lg:h-[35rem] lg:w-[35rem]" />

                    <div class="hero-info flex flex-col space-y-4">
                        <h1 class="text-[#2d2e32] text-5xl md:text-6xl font-semibold">Full-Stack Web Developer</h1>
                        <p class="text-[#767676] text-lg font-normal">Hi, I'm Harrison Max-Wilson. A passionate Web Developer based in Bournemouth, United Kingdom. 📍</p>
                        <span class="flex text-4xl space-x-4 justify-center lg:justify-start">
                            <a aria-label="linkedin" target="_blank" rel="noreferrer" href="https://www.linkedin.com/in/HMaxWilson/">
                                <FontAwesomeIcon icon="fa-brands fa-linkedin" />
                            </a>
                            <a aria-label="github" target="_blank" rel="noreferrer" href="https://github.com/HMaxWilson">
                                <FontAwesomeIcon icon="fa-brands fa-github" />
                            </a>
                        </span>

                        <div class="skills items-center color-[#767676] flex flex-col text-2xl space-y-4">
                            <p class="border-b-2 border-[#2d2e380] font-semibold pb-2">Tech Stack</p>
                            <div class="logos">
                                <ul class="flex flex-wrap gap-4 justify-center">
                                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/git.svg" alt="Github" />
                                    </li>
                                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/html.svg" alt="HTML" />
                                    </li>
                                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/css3.svg" alt="CSS3" />
                                    </li>
                                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/javascript.svg" alt="JavaScript" />
                                    </li>
                                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/vuejs.svg" alt="VueJS" />
                                    </li>
                                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/nuxtjs.svg" alt="NuxtJS" />
                                    </li>
                                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/tailwind.svg" alt="TailwindCSS" />
                                    </li>
                                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/php.svg" alt="PHP" />
                                    </li>
                                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                                        <img class="h-auto w-8" src="/images/tech/laravel.svg" alt="Laravel" />
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