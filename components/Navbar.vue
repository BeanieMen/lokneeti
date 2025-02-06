<template>
  <nav class="sm:block hidden">
    <div
      class="fixed md:left-2 lg:left-4 top-[50%] translate-y-[-50%] z-50 group flex flex-col gap-4 p-4 pl-5 transition-all ease-in-out duration-300 hover:w-52 lg:w-16 overflow-hidden gap-y-10"
      style="border-radius: 2rem; background: rgba(34, 34, 34, 0.50); backdrop-filter: blur(3px)">
      <!-- Home Button -->
      <button class="flex items-center gap-4 text-white hover:text-gray-300 transition-colors">
        <LucideHome class="w-8 h-8 min-w-6" />
        <span class="opacity-0 group-hover:opacity-100 transition-opacity duration-300 whitespace-nowrap">
          Home
        </span>
      </button>

      <!-- FAQ Button -->
      <button class="flex items-center gap-4 text-white hover:text-gray-300 transition-colors">
        <LucideHelpCircle class="w-8 h-8 min-w-6" />
        <span class="opacity-0 group-hover:opacity-100 transition-opacity duration-300 whitespace-nowrap">
          FAQ
        </span>
      </button>

      <!-- Contact Button -->
      <button class="flex items-center gap-4 text-white hover:text-gray-300 transition-colors">
        <LucideMail class="w-8 h-8 min-w-6" />
        <span class="opacity-0 group-hover:opacity-100 transition-opacity duration-300 whitespace-nowrap">
          Contact
        </span>
      </button>
    </div>
  </nav>
</template>