<template>
  <footer class="bg-[#2d2e32] py-10 w-full">
    <div class="container mx-auto max-w-[#107rem] px-8">
        <div class="items-center flex justify-between">
            <h3 class="text-white font-semibold text-sm">Copyright © 2023</h3>
            <div class="footer-socials flex gap-4">
                <a class="text-2xl text-white" aria-label="linkedin" target="_blank" rel="noreferrer" href="https://www.linkedin.com/in/HMaxWilson/">
                    <FontAwesomeIcon icon="fa-brands fa-linkedin" />
                </a>
                <a class="text-2xl text-white" aria-label="github" target="_blank" rel="noreferrer" href="https://github.com/HMaxWilson">
                    <FontAwesomeIcon icon="fa-brands fa-github" />
                </a>
            </div>
        </div>
    </div>
  </footer>
</template>

<script setup lang="ts">
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";
</script>