---
layout: page
permalink: /music/
---

<section class="px-4 py-8 max-w-xl mx-auto space-y-6">

  <!-- Song Card -->
  <div class="group relative overflow-hidden rounded-xl shadow-lg">
    <!-- Image Cover -->
    <img 
      src="/images/sza.jpg" 
      alt="SZA Track Cover" 
      class="w-full h-auto object-cover transition-transform duration-300 group-hover:scale-105 rounded-xl"
      loading="lazy"
    />

    <!-- Overlay Text -->
    <div class="absolute bottom-0 left-0 right-0 bg-black/60 text-white p-4">
      <h2 class="text-xl font-bold">SZA - Forest Dreams</h2>
      <p class="text-sm">Chill / Ambient · Made in Fukuoka</p>
    </div>
  </div>

  <!-- Audio Player -->
  <audio controls class="w-full rounded-md mt-2">
    <source src="/music/sza.mp3" type="audio/mpeg" />
    Your browser does not support the audio element.
  </audio>

</section>
