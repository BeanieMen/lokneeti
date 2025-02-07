<template>
  <div class="bg-[#161616] text-white min-h-screen relative">
    <Navbar />

    <!-- Hero Section -->
    <section class="relative flex flex-col items-center justify-center text-center h-screen px-4">
      <!-- Particles Background (fills the hero section) -->
      <div class="absolute inset-0 pointer-events-none z-0">
        <Particles />
      </div>
      <!-- Hero Content (placed above particles) -->
      <div class="relative z-10">
        <h1 class="text-5xl font-bold text-[#F0720B]">Welcome to Lokneeti MUN</h1>
        <p class="text-lg mt-4 max-w-2xl">
          Join the most engaging Model United Nations conference and experience diplomacy, debate, and global leadership.
        </p>
        <button
          class="mt-6 px-6 py-3 bg-[#F0720B] font-semibold rounded-lg hover:bg-opacity-90 transition">
          Register Now
        </button>
      </div>
    </section>


    <!-- Features Section -->
    <section class="py-20 px-6 text-center">
      <h2 class="text-4xl font-semibold text-[#F0720B]">Why Join Us?</h2>
      <div class="mt-8 grid grid-cols-1 md:grid-cols-3 gap-8 max-w-5xl mx-auto">
        <div class="p-6 rounded-lg border border-[#F0720B]">
          <h3 class="text-2xl font-semibold">Global Networking</h3>
          <p class="mt-2">
            Connect with delegates from around the world and build lifelong relationships.
          </p>
        </div>
        <div class="p-6 rounded-lg border border-[#F0720B]">
          <h3 class="text-2xl font-semibold">Diplomatic Experience</h3>
          <p class="mt-2">
            Enhance your public speaking, negotiation, and leadership skills in real-time simulations.
          </p>
        </div>
        <div class="p-6 rounded-lg border border-[#F0720B]">
          <h3 class="text-2xl font-semibold">Engaging Debates</h3>
          <p class="mt-2">
            Tackle pressing global issues and propose innovative solutions in structured debates.
          </p>
        </div>
      </div>
    </section>

    <!-- Call to Action -->
    <section class="py-20 px-6 text-center">
      <h2 class="text-4xl font-semibold">Ready to Join?</h2>
      <p class="mt-4 max-w-2xl mx-auto">
        Sign up now and be part of an unforgettable Lokneeti mun experience!
      </p>
      <button
        class="mt-6 px-6 py-3 bg-[#F0720B] text-[#161616] font-semibold rounded-lg hover:bg-opacity-90 transition">
        Sign Up
      </button>
    </section>

    <!-- Footer -->
    <footer class="py-6 text-center text-sm">
      &copy; 2025 Lokneeti mun. All rights reserved.
    </footer>
  </div>
</template>
