<template>
    <section class="relative z-10 overflow-hidden pt-28 lg:pt-[150px] bg-white dark:bg-gray-dark">
          <div class="container">
              <div class="-mx-4 flex flex-wrap items-center">
                  <div class="w-full px-4 md:w-8/12 lg:w-7/12">
                      <div class="mb-8 max-w-[570px] md:mb-0 lg:mb-12">
                          <h1 class="mb-5 text-2xl font-bold text-black dark:text-white sm:text-3xl">Сертификаты</h1>
                          <!-- <p class="text-base font-medium leading-relaxed text-body-color">Сертификаты</p> -->
                      </div>
                  </div>
                  <div class="w-full px-4 md:w-4/12 lg:w-5/12">
                      <div class="text-end">
                          <ul class="flex items-center md:justify-end">
                              <li class="flex items-center"><router-link class="pr-1 text-base font-medium text-body-color hover:text-primary" to="/">Главная</router-link><span class="mr-3 block h-2 w-2 rotate-45 border-r-2 border-t-2 border-body-color"></span></li>
                              <li class="text-base font-medium text-primary">Сертификаты</li>
                          </ul>
                      </div>
                  </div>
              </div>
          </div>
          <div>
              <span class="absolute left-0 top-0 z-[-1]">
                  <svg width="287" height="254" viewBox="0 0 287 254" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <path opacity="0.1" d="M286.5 0.5L-14.5 254.5V69.5L286.5 0.5Z" fill="url(#paint0_linear_111:578)"></path>
                      <defs>
                          <linearGradient id="paint0_linear_111:578" x1="-40.5" y1="117" x2="301.926" y2="-97.1485" gradientUnits="userSpaceOnUse">
                              <stop stop-color="#4A6CF7"></stop>
                              <stop offset="1" stop-color="#4A6CF7" stop-opacity="0"></stop>
                          </linearGradient>
                      </defs>
                  </svg>
              </span>
              <span class="absolute right-0 top-0 z-[-1]">
                  <svg width="628" height="258" viewBox="0 0 628 258" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <path opacity="0.1" d="M669.125 257.002L345.875 31.9983L524.571 -15.8832L669.125 257.002Z" fill="url(#paint0_linear_0:1)"></path>
                      <path opacity="0.1" d="M0.0716344 182.78L101.988 -15.0769L142.154 81.4093L0.0716344 182.78Z" fill="url(#paint1_linear_0:1)"></path>
                      <defs>
                          <linearGradient id="paint0_linear_0:1" x1="644" y1="221" x2="429.946" y2="37.0429" gradientUnits="userSpaceOnUse">
                              <stop stop-color="#4A6CF7"></stop>
                              <stop offset="1" stop-color="#4A6CF7" stop-opacity="0"></stop>
                          </linearGradient>
                          <linearGradient id="paint1_linear_0:1" x1="18.3648" y1="166.016" x2="105.377" y2="32.3398" gradientUnits="userSpaceOnUse">
                              <stop stop-color="#4A6CF7"></stop>
                              <stop offset="1" stop-color="#4A6CF7" stop-opacity="0"></stop>
                          </linearGradient>
                      </defs>
                  </svg>
              </span>
          </div>
      </section>
      
      <CertificatesList />
  </template>
    
  <script setup>
    import CertificatesList from '../components/CertificatesList.vue';
  </script>
  
  <style>
  
  </style>