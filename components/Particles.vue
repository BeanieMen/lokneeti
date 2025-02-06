<template>
  <!-- Apply the gradient background using Tailwind CSS -->
  <div class="bg-gradient-to-b from-[#081122] to-[#132244]">
    <NuxtParticles id="tsparticles" :options="options" @load="onLoad" />
  </div>
</template>

<script setup lang="ts">
import type { Container } from 'tsparticles-engine'

const options = {
  fullScreen: {
    enable: true,
    zIndex: 0
  },
  background: {
    color: {
      value: "transparent"
    }
  },
  fpsLimit: 60,
  interactivity: {
    events: {
      onClick: {
        enable: true,
        mode: "push" // Add particles on click
      },
      onHover: {
        enable: true,
        mode: "repulse" // Repulse particles on hover
      },
      resize: true
    },
    modes: {
      push: {
        quantity: 4
      },
      repulse: {
        distance: 100,
        duration: 0.4
      }
    }
  },
  particles: {
    color: {
      value: "#ffffff"
    },
    links: {
      color: "#ffffff",
      distance: 150,
      enable: true,
      opacity: 0.4,
      width: 1
    },
    collisions: {
      enable: true
    },
    move: {
      direction: "none",
      enable: true,
      outModes: {
        default: "bounce"
      },
      random: false,
      speed: 3,
      straight: false
    },
    number: {
      density: {
        enable: true,
        area: 600
      },
      value: 200
    },
    opacity: {
      value: 0.5,
      random: false,
      anim: {
        enable: false,
        speed: 1,
        opacity_min: 0.1,
        sync: false
      }
    },
    shape: {
      type: "circle"
    },
    size: {
      value: 3,
      random: true,
      anim: {
        enable: false,
        speed: 40,
        size_min: 0.1,
        sync: false
      }
    }
  },
  detectRetina: true

}

const onLoad = (container: Container) => {
  // Example: Pause the particle animation and resume after 2 seconds
  container.pause()
  setTimeout(() => container.play(), 2000)
}
</script>