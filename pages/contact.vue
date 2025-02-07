<template>
    <div class="bg-[#161616] min-h-screen h-screen max-h-screen text-white w-full p-6 md:p-12 lg:p-20 md:py-16 pt-[32px] sm:pt-[48px]">
      <Navbar />
      <div class="max-w-7xl mx-auto ml-5 space-y-12">
        <div class="flex items-start justify-between pb-8 md:pb-16">
          <div class="space-y-4">
            <div class="flex items-center justify-between">
              <h1 class="text-[42px] text-[#F0720B] md:text-5xl lg:text-7xl font-black leading-tight">
                How can we<br />Help you?
              </h1>
              <div class="block md:hidden">
                <img
                  alt="phone"
                  loading="lazy"
                  width="100"
                  height="100"
                  decoding="async"
                  class="hidden sm:block"
                  src="/phone.webp"
                  style="color: transparent;"
                />
              </div>
            </div>
            <p class="xxs:text-lg md:text-xl font-medium max-w-lg md:max-w-xl lg:max-w-2xl xl:maw-w-3xl text-white">
              At Lokneeti MUN, we prioritize impactful debates and diplomacy! Have questions, need assistance, or want to connect? Reach out to us!
            </p>
          </div>
          <div class="hidden md:block mx-auto">
            <img
              alt="phone"
              loading="lazy"
              width="268"
              height="270"
              decoding="async"
              class="md:w-[168px] lg:w-[200px] xl:w-[220px]"
              src="/phone.webp"
              style="color: transparent;"
            />
          </div>
        </div>
  
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div class="space-y-2">
            <h2 class="text-3xl md:text-4xl font-black text-[#F0720B]">Call Us</h2>
            <div class="flex flex-row gap-8 font-medium">
              <div>
                <p>+91 98717 88959</p>
                <p class="text-base font-medium">Navyam Anand </p>
              </div>
              <div>
                <p>+91 89299 19964</p>
                <p class="text-base font-medium">Akshat Singh</p>
              </div>
            </div>
          </div>
  
          <div class="space-y-2">
            <h2 class="text-3xl md:text-4xl font-black text-[#F0720B]">Mail Us</h2>
            <div class="space-y-1 flex flex-col font-medium">
              <a target="_blank" href="mailto:hackbyte@iiitdmj.ac.in">none@none.com</a>
            </div>
          </div>
  
          <div class="space-y-2 col-span-2 md:col-span-1">
            <h2 class="text-3xl md:text-4xl font-black text-[#F0720B]">Address</h2>
            <p class="text-base font-medium">
              None<br />
              None
            </p>
          </div>
        </div>
        <!-- <MapAndMode/> -->

      </div>
    </div>
  </template>
  