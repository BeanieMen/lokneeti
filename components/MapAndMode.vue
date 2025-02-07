<template>
     <div class="space-y-6 mt-25">
          <h2 class="text-3xl md:text-4xl xl:text-5xl font-black">Reaching IIITDM Jabalpur</h2>
          <div class="aspect-video w-full rounded-3xl overflow-hidden">
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3668.4774721298!2d80.02231931544636!3d23.176386884867444!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3981ae1a0fb6a97d%3A0x44020f94f795d69f!2sIIITDM%20Jabalpur!5e0!3m2!1sen!2sin!4v1629789876543!5m2!1sen!2sin"
              width="100%"
              height="100%"
              allowfullscreen
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
              style="border: 0;"
            ></iframe>
          </div>
  
          <!-- Mode of Transport Cards -->
          <div class="grid grid-cols-1 md:grid-cols-3 gap-6 md:py-16 py-2">
            <!-- Card: By Train -->
            <div class="rounded-lg border border-[#F0720B] bg-[#161616] p-4 space-y-4">
              <div class="flex md:items-start items-center gap-6 md:flex-col flex-row">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                  fill="none"
                  stroke="currentColor"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  class="lucide lucide-tram-front size-12 text-[#F0720B] bg-[#F0720B]/30 p-2 rounded-lg"
                >
                  <rect width="16" height="16" x="4" y="3" rx="2" />
                  <path d="M4 11h16" />
                  <path d="M12 3v8" />
                  <path d="m8 19-2 3" />
                  <path d="m18 22-2-3" />
                  <path d="M8 15h.01" />
                  <path d="M16 15h.01" />
                </svg>
                <h3 class="font-black text-2xl text-[#F0720B]">By Train</h3>
              </div>
              <p class="md:text-base text-base text-white font-medium">
                Book tickets from IRCTC : The campus is <b class="text-[#F0720B]">10kms from the Railway Terminal</b>
                and auto fare is usually around <b class="text-[#F0720B]">₹200-₹250</b>.
              </p>
            </div>
  
            <!-- Card: By Flight -->
            <div class="rounded-lg border border-[#F0720B] bg-[#161616] p-4 space-y-4">
              <div class="flex md:items-start items-center gap-6 md:flex-col flex-row">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                  fill="none"
                  stroke="currentColor"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  class="lucide lucide-plane size-12 text-[#F0720B] bg-[#F0720B]/30 p-2 rounded-lg"
                >
                  <path d="M17.8 19.2 16 11l3.5-3.5C21 6 21.5 4 21 3c-1-.5-3 0-4.5 1.5L13 8 4.8 6.2c-.5-.1-.9.1-1.1.5l-.3.5c-.2.5-.1 1 .3 1.3L9 12l-2 3H4l-1 1 3 2 2 3 1-1v-3l3-2 3.5 5.3c.3.4.8.5 1.3.3l.5-.2c.4-.3.6-.7.5-1.2z" />
                </svg>
                <h3 class="font-black text-2xl text-[#F0720B]">By Flight</h3>
              </div>
              <p class="md:text-base text-base text-white font-medium">
                Daily flights from <b class="text-[#F0720B]">Delhi, Mumbai, Hyderabad, Indore and Bilaspur</b>.
                From <b class="text-[#F0720B]">Bangalore</b>, connecting flights are available.
              </p>
            </div>
  
            <!-- Card: By Bus -->
            <div class="rounded-lg border border-[#F0720B] bg-[#161616] p-4 space-y-4">
              <div class="flex md:items-start items-center gap-6 md:flex-col flex-row">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                  fill="none"
                  stroke="currentColor"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  class="lucide lucide-bus size-12 text-[#F0720B] bg-[#F0720B]/30 p-2 rounded-lg"
                >
                  <path d="M8 6v6" />
                  <path d="M15 6v6" />
                  <path d="M2 12h19.6" />
                  <path d="M18 18h3s.5-1.7.8-2.8c.1-.4.2-.8.2-1.2 0-.4-.1-.8-.2-1.2l-1.4-5C20.1 6.8 19.1 6 18 6H4a2 2 0 0 0-2 2v10h3" />
                  <circle cx="7" cy="18" r="2" />
                  <path d="M9 18h5" />
                  <circle cx="16" cy="18" r="2" />
                </svg>
                <h3 class="font-black text-2xl text-[#F0720B]">By Bus</h3>
              </div>
              <p class="md:text-base text-base text-white font-medium">
                Only suggested if you live around 8-10hrs from Jabalpur.
                <b class="text-[#F0720B]">ISBT (Pandit Deen Dayal Bus Stand)</b> is around 13km from the venue,
                auto fare is usually around <b class="text-[#F0720B]">₹400-₹450</b>.
              </p>
            </div>
          </div>
        </div>
</template>