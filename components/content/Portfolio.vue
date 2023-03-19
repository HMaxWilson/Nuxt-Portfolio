<template>
  <section id="portfolio" class="portfolio bg-[#fff] py-16">
    <div class="container mx-auto max-w-[68rem] px-4">
      <div class="content flex flex-col space-y-4">
        <h3 class="text-[#147efb] text-2xl font-semibold uppercase">Portfolio</h3>
        <p class="text-[#2d2e32] text-3xl">
          More projects available to view at
          <a class="text-blue-800 hover:text-blue-600" href="https://www.github.com/HMaxWilson" target="_blank">Github</a>
        </p>
        <div class="projects flex flex-col space-y-12">
          <div class="project flex flex-col md:flex-row gap-4 p-4 bg-white rounded-lg shadow-md border-2 w-full">
            <div class="project-img bg-[#75757533] mb-auto rounded-lg shadow-lg overflow-hidden md:max-w-[45%]">
              <img class="h-auto w-full" src="/images/portfolio/igdb.gif" alt="IGDB Project">
            </div>
            <div class="project-text flex flex-col text-center md:text-left w-full">
              <h3 class="text-[#2d2e32] text-2xl mb-4 relative font-semibold uppercase">Game Aggregator</h3>
              <p class="text-[#767676] text-2xl text-center md:text-left">An ongoing development into creating a video game aggregator using a 3rd party API in a project.</p>
              <div class="skills items-center md:items-end color-[#767676] flex flex-col text-2xl space-y-4">
                <p class="border-b-2 border-[#2d2e380] font-semibold pb-2"></p>
                <div class="logos">
                  <ul class="flex flex-wrap gap-4 justify-start lg:justify-center">
                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                      <img class="h-auto w-8" src="/images/tech/laravel.svg" alt="Laravel" />
                    </li>
                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                      <img class="h-auto w-8" src="/images/tech/php.svg" alt="PHP" />
                    </li>
                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                      <img class="h-auto w-8" src="/images/tech/tailwind.svg" alt="TailwindCSS" />
                    </li>
                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                      <img class="h-auto w-8" src="/images/tech/html.svg" alt="HTML" />
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>

          <div class="project flex flex-col-reverse md:flex-row gap-4 p-4 bg-white rounded-lg shadow-md border-2 w-full">
            <div class="project-text flex flex-col text-center md:text-left w-full">
              <h3 class="text-[#2d2e32] text-2xl mb-4 relative font-semibold uppercase">Amplify</h3>
              <p class="text-[#767676] text-2xl text-center md:text-left">A follow along project replicating Spotify 2017, by Reece Kenney, available on Udemy. Using PHP, HTML CSS, JS and JQuery</p>
              <div class="skills items-center md:items-start color-[#767676] flex flex-col text-2xl space-y-4">
                <p class="border-b-2 border-[#2d2e380] font-semibold pb-2"></p>
                <div class="logos">
                  <ul class="flex flex-wrap gap-4 justify-start lg:justify-center">
                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                      <img class="h-auto w-8" src="/images/tech/html.svg" alt="HTML" />
                    </li>
                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                      <img class="h-auto w-8" src="/images/tech/php.svg" alt="PHP" />
                    </li>
                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                      <img class="h-auto w-8" src="/images/tech/css3.svg" alt="CSS3" />
                    </li>
                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                      <img class="h-auto w-8" src="/images/tech/javascript.svg" alt="JavaScript" />
                    </li>
                  </ul>
                </div>
              </div>
            </div>
            <div class="project-img bg-[#75757533] mb-auto rounded-lg shadow-lg overflow-hidden md:max-w-[45%]">
              <img class="h-auto w-full" src="/images/portfolio/amplify.gif" alt="Amplify Project">
            </div>
          </div>

          <div class="project flex flex-col md:flex-row gap-4 p-4 bg-white rounded-lg shadow-md border-2 w-full">
            <div class="project-img bg-[#75757533] mb-auto rounded-lg shadow-lg overflow-hidden md:max-w-[45%]">
              <img class="h-auto w-full" src="/images/portfolio/replications.gif" alt="Replications Project">
            </div>
            <div class="project-text flex flex-col text-center md:text-left w-full">
              <h3 class="text-[#2d2e32] text-2xl mb-4 relative font-semibold uppercase">Replications</h3>
              <p class="text-[#767676] text-2xl text-center md:text-left">A group of projects that I have replicated from other websites, to help me learn and understand how they are created using css technologies.</p>
              <div class="skills items-center md:items-end color-[#767676] flex flex-col text-2xl space-y-4">
                <p class="border-b-2 border-[#2d2e380] font-semibold pb-2"></p>
                <div class="logos">
                  <ul class="flex flex-wrap gap-4 justify-start lg:justify-center">
                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                      <img class="h-auto w-8" src="/images/tech/nuxtjs.svg" alt="NuxtJS" />
                    </li>
                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                      <img class="h-auto w-8" src="/images/tech/bootstrap.svg" alt="Bootstrap" />
                    </li>
                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                      <img class="h-auto w-8" src="/images/tech/tailwind.svg" alt="TailwindCSS" />
                    </li>
                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                      <img class="h-auto w-8" src="/images/tech/css3.svg" alt="CSS3" />
                    </li>
                    <li class="items-center bg-white rounded-full shadow-md flex h-14 w-14 justify-center">
                      <img class="h-auto w-8" src="/images/tech/html.svg" alt="HTML" />
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>