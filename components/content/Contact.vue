<template>
  <section id="contact" class="hero bg-[#f9f9f9] flex flex-col h-auto py-12 relative w-full">
    <div class="container mx-auto max-w-[107rem] px-4 lg:px-16">
      <div class="content flex flex-col">
        <div class="contact-text">
          <h3 class="text-[#147efb] text-2xl font-semibold mb-4 uppercase">Contact</h3>
          <p class="text-[#2d2e32] text-3xl mb-12">Get in touch!</p>
        </div>
        <div class="contact-content flex flex-wrap gap-16 mt-18">
          <div class="contact-method items-center flex gap-3">
            <span class="bg-white rounded-full shadow-lg p-5">
              <FontAwesomeIcon icon="fa-solid fa-envelope" />
            </span>
            <div class="contact-info flex flex-col gap-2">
              <h3 class="text-[#2d2e32] text-xl font-semibold">Location</h3>
              <p class="text-[#767676] text-lg">Bournemouth, United Kingdom</p>
            </div>
          </div>
          <div class="contact-method items-center flex gap-3">
            <span class="bg-white rounded-full shadow-lg p-5">
              <FontAwesomeIcon icon="fa-solid fa-envelope" />
            </span>
            <div class="contact-info flex flex-col gap-2">
              <h3 class="text-[#2d2e32] text-xl font-semibold">Email</h3>
              <p class="text-[#767676] text-lg"><a href="mailto:H.MaxWilson@hotmail.com"></a>H.MaxWilson@hotmail.com</p>
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