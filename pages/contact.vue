<template>
  <div class="bg-[#161616] min-h-screen text-white w-full p-6 md:p-12 lg:px-20 lg:py-16 pt-[32px] sm:pt-[48px]">
    <Navbar />
    <div class="max-w-7xl mx-auto space-y-8 md:space-y-16">
      <div class="flex flex-col md:flex-row justify-between gap-6 md:gap-12 pb-8 md:pb-16">
        <div class="space-y-4 md:space-y-6 flex-1">
          <div class="flex justify-between items-start">
            <h1 class="text-4xl md:text-5xl lg:text-7xl text-[#F0720B] font-black leading-tight">
              How can we<br />Help you?
            </h1>
            <img
              alt="phone"
              width="100"
              height="100"
              class="sm:block md:hidden w-20 sm:w-24"
              src="/phone.webp"
            />
          </div>
          <p class="text-lg md:text-xl font-medium max-w-prose text-white/90">
            At Lokneeti MUN, we prioritize impactful debates and diplomacy! Have questions, need assistance, or want to connect? Reach out to us!
          </p>
        </div>
        <div class="hidden md:block flex-shrink-0">
          <img
            alt="phone"
            width="268"
            height="270"
            class="w-40 lg:w-56 xl:w-64"
            src="/phone.webp"
          />
        </div>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-6 md:gap-8">
        <div class="space-y-3 md:space-y-4">
          <h2 class="text-3xl md:text-4xl font-black text-[#F0720B]">Call Us</h2>
          <div class="flex flex-col sm:flex-row md:flex-col gap-4 font-medium">
            <div>
              <p>+91 98717 88959</p>
              <p class="text-base text-white/80">Navyam Anand</p>
            </div>
            <div>
              <p>+91 89299 19964</p>
              <p class="text-base text-white/80">Akshat Singh</p>
            </div>
          </div>
        </div>

        <div class="space-y-3 md:space-y-4">
          <h2 class="text-3xl md:text-4xl font-black text-[#F0720B]">Mail Us</h2>
          <div class="space-y-1 font-medium">
            <a href="mailto:bitch@bitch.ac.in" class="block hover:text-[#F0720B] transition-colors">
              none@none.com
            </a>
          </div>
        </div>

        <div class="space-y-3 md:space-y-4">
          <h2 class="text-3xl md:text-4xl font-black text-[#F0720B]">Address</h2>
          <p class="text-base font-medium text-white/80">
            None<br />
            None
          </p>
        </div>
      </div>
    </div>
  </div>
</template>