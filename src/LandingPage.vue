<script setup>
// You can add reactive data here if needed
</script>

<template>
  <div class="bg-[#0F0F12] text-white">
    <!-- Hero Section -->
    <div class="min-h-screen flex flex-col relative">
      <!-- Top bar: Logo and Menu -->
      <header class="flex justify-between items-center p-6 z-10">
        <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/Vector.png" alt="Logo" class="h-8"/>
        <button class="bg-white text-black rounded-full px-6 py-2 font-medium hover:bg-gray-100 transition-colors duration-300">
          MENU
        </button>
      </header>

      <!-- Main Quote Section -->
      <main class="flex-grow flex items-center justify-center text-center px-6">
        <h1 class="text-4xl md:text-6xl lg:text-7xl font-bold max-w-4xl leading-tight">
          "Il n'y a pas de richesse sans créativité"
        </h1>
      </main>

      <!-- Vertical Honors box -->
      <aside class="absolute right-0 top-1/2 transform -translate-y-1/2 p-4 bg-white text-black h-48 w-16 flex flex-col items-center justify-center">
        <div class="font-bold text-lg mb-4">W.</div>
        <div class="text-sm transform -rotate-90 whitespace-nowrap">Honors</div>
      </aside>

      <!-- Scroll indicator -->
      <div class="absolute bottom-8 left-1/2 transform -translate-x-1/2 flex flex-col items-center animate-bounce">
        <div class="w-px h-12 bg-white opacity-50 mb-2"></div>
        <div class="text-xs opacity-70 tracking-widest">SCROLL</div>
      </div>
    </div>

    <!-- Enhanced Moving Text Section -->
    <section class="w-full py-16 overflow-hidden bg-[#0F0F12] relative">
      <!-- Gradient masks for smooth fade-out effect -->
      <div class="absolute inset-0 pointer-events-none z-10">
        <div class="absolute left-0 top-0 w-32 h-full bg-gradient-to-r from-[#0F0F12] to-transparent"></div>
        <div class="absolute right-0 top-0 w-32 h-full bg-gradient-to-l from-[#0F0F12] to-transparent"></div>
      </div>
      
      <!-- Top moving line (left to right) -->
      <div class="relative mb-8">
        <div class="whitespace-nowrap animate-scroll-right text-gray-400 text-lg font-medium tracking-wide">
          <div class="inline-flex">
            <!-- First complete set -->
            <span class="inline-flex items-center mx-12">
              <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/star-outline.svg.png" alt="star" class="h-4 w-4 mr-4 opacity-60"/>
              Directrice Artistique
            </span>
            <span class="inline-flex items-center mx-12">
              <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/star-outline.svg.png" alt="star" class="h-4 w-4 mr-4 opacity-60"/>
              Webdesign
            </span>
            <span class="inline-flex items-center mx-12">
              <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/star-outline.svg.png" alt="star" class="h-4 w-4 mr-4 opacity-60"/>
              Print
            </span>
            <span class="inline-flex items-center mx-12">
              <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/star-outline.svg.png" alt="star" class="h-4 w-4 mr-4 opacity-60"/>
              Illustration
            </span>
            <!-- Duplicate set for seamless loop -->
            <span class="inline-flex items-center mx-12">
              <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/star-outline.svg.png" alt="star" class="h-4 w-4 mr-4 opacity-60"/>
              Directrice Artistique
            </span>
            <span class="inline-flex items-center mx-12">
              <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/star-outline.svg.png" alt="star" class="h-4 w-4 mr-4 opacity-60"/>
              Webdesign
            </span>
            <span class="inline-flex items-center mx-12">
              <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/star-outline.svg.png" alt="star" class="h-4 w-4 mr-4 opacity-60"/>
              Print
            </span>
            <span class="inline-flex items-center mx-12">
              <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/star-outline.svg.png" alt="star" class="h-4 w-4 mr-4 opacity-60"/>
              Illustration
            </span>
          </div>
        </div>
      </div>
      
      <!-- Bottom moving line (right to left) -->
      <div class="relative">
        <div class="whitespace-nowrap animate-scroll-left text-gray-400 text-lg font-medium tracking-wide">
          <div class="inline-flex">
            <!-- First complete set -->
            <span class="inline-flex items-center mx-12">
              <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/star-outline.svg.png" alt="star" class="h-4 w-4 mr-4 opacity-60"/>
              UI Design
            </span>
            <span class="inline-flex items-center mx-12">
              <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/star-outline.svg.png" alt="star" class="h-4 w-4 mr-4 opacity-60"/>
              UX Design
            </span>
            <span class="inline-flex items-center mx-12">
              <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/star-outline.svg.png" alt="star" class="h-4 w-4 mr-4 opacity-60"/>
              Motion Design
            </span>
            <span class="inline-flex items-center mx-12">
              <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/star-outline.svg.png" alt="star" class="h-4 w-4 mr-4 opacity-60"/>
              Interactive Design
            </span>
            <!-- Duplicate set for seamless loop -->
            <span class="inline-flex items-center mx-12">
              <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/star-outline.svg.png" alt="star" class="h-4 w-4 mr-4 opacity-60"/>
              UI Design
            </span>
            <span class="inline-flex items-center mx-12">
              <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/star-outline.svg.png" alt="star" class="h-4 w-4 mr-4 opacity-60"/>
              UX Design
            </span>
            <span class="inline-flex items-center mx-12">
              <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/star-outline.svg.png" alt="star" class="h-4 w-4 mr-4 opacity-60"/>
              Motion Design
            </span>
            <span class="inline-flex items-center mx-12">
              <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/star-outline.svg.png" alt="star" class="h-4 w-4 mr-4 opacity-60"/>
              Interactive Design
            </span>
          </div>
        </div>
      </div>
    </section>

    <!-- Portfolio Grid -->
    <section class="py-16 px-6 max-w-7xl mx-auto">
      <div class="grid md:grid-cols-2 gap-8">
        <!-- Project 1 - Digital Platform -->
        <div class="group bg-gradient-to-br from-blue-600 to-blue-800 rounded-2xl p-8 h-80 flex flex-col justify-between relative overflow-hidden cursor-pointer transform transition-all duration-300 hover:-translate-y-2 hover:shadow-2xl hover:shadow-blue-500/20">
          <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/screen.png" alt="Digital Platform" class="absolute inset-0 w-full h-full object-cover rounded-2xl opacity-80 group-hover:opacity-100 transition-opacity duration-300 z-0"/>
          <div class="z-10">
            <h3 class="text-2xl font-bold mb-2 group-hover:text-blue-100 transition-colors">Digital Platform</h3>
            <p class="text-blue-100 opacity-80 text-sm tracking-wide">Web Development • UI/UX</p>
          </div>
          <div class="absolute top-4 right-4 w-12 h-12 bg-white bg-opacity-20 rounded-full flex items-center justify-center group-hover:bg-opacity-30 transition-all duration-300 group-hover:scale-110 z-10">
            <span class="text-white font-bold transform group-hover:translate-x-1 transition-transform">→</span>
          </div>
          <div class="absolute bottom-0 right-0 w-32 h-32 bg-white bg-opacity-10 rounded-full transform translate-x-8 translate-y-8 group-hover:scale-110 transition-transform duration-500 z-0"></div>
        </div>

        <!-- Project 2 - OPENTRI -->
        <div class="group bg-gradient-to-br from-blue-500 to-cyan-600 rounded-2xl p-8 h-80 flex flex-col justify-between relative overflow-hidden cursor-pointer transform transition-all duration-300 hover:-translate-y-2 hover:shadow-2xl hover:shadow-cyan-500/20">
           <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/watter.png" alt="OPENTRI" class="absolute inset-0 w-full h-full object-cover rounded-2xl opacity-80 group-hover:opacity-100 transition-opacity duration-300 z-0"/>
          <div class="z-10">
            <h3 class="text-3xl font-bold mb-2 group-hover:text-cyan-100 transition-colors">OPENTRI</h3>
            <p class="text-cyan-100 opacity-80 text-sm tracking-wide">Brand Identity • Digital</p>
          </div>
          <div class="absolute top-4 right-4 w-12 h-12 bg-white bg-opacity-20 rounded-full flex items-center justify-center group-hover:bg-opacity-30 transition-all duration-300 group-hover:scale-110 z-10">
            <span class="text-white font-bold transform group-hover:translate-x-1 transition-transform">→</span>
          </div>
          <div class="absolute -bottom-8 -right-8 text-8xl font-bold text-white opacity-10 group-hover:opacity-20 transition-opacity duration-300 z-0">O</div>
        </div>

        <!-- Project 3 - Creative Studio -->
        <div class="group bg-gradient-to-br from-purple-900 to-black rounded-2xl p-8 h-80 flex flex-col justify-between relative overflow-hidden cursor-pointer transform transition-all duration-300 hover:-translate-y-2 hover:shadow-2xl hover:shadow-purple-500/20">
           <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/volcano.png" alt="Creative Studio" class="absolute inset-0 w-full h-full object-cover rounded-2xl opacity-80 group-hover:opacity-100 transition-opacity duration-300 z-0"/>
          <div class="z-10">
            <h3 class="text-2xl font-bold mb-2 group-hover:text-purple-200 transition-colors">Creative Studio</h3>
            <p class="text-purple-200 opacity-80 text-sm tracking-wide">Visual Identity • Print</p>
          </div>
          <div class="absolute top-4 right-4 w-12 h-12 bg-white bg-opacity-20 rounded-full flex items-center justify-center group-hover:bg-opacity-30 transition-all duration-300 group-hover:scale-110 z-10">
            <span class="text-white font-bold transform group-hover:translate-x-1 transition-transform">→</span>
          </div>
          <div class="absolute bottom-4 left-4 w-24 h-24 bg-purple-500 bg-opacity-30 rounded-lg transform rotate-12 group-hover:rotate-45 group-hover:scale-110 transition-all duration-500 z-0"></div>
        </div>

        <!-- Project 4 - LAUNCH -->
        <div class="group bg-gradient-to-br from-indigo-600 to-purple-700 rounded-2xl p-8 h-80 flex flex-col justify-between relative overflow-hidden cursor-pointer transform transition-all duration-300 hover:-translate-y-2 hover:shadow-2xl hover:shadow-indigo-500/20">
           <img src="/home/jurgen/landing_pages/wolvesart/src/components/img/eagle.png" alt="LAUNCH" class="absolute inset-0 w-full h-full object-cover rounded-2xl opacity-80 group-hover:opacity-100 transition-opacity duration-300 z-0"/>
          <div class="z-10">
            <h3 class="text-3xl font-bold mb-2 group-hover:text-indigo-200 transition-colors">LAUNCH</h3>
            <p class="text-indigo-200 opacity-80 text-sm tracking-wide">Product Launch • Campaign</p>
          </div>
          <div class="absolute top-4 right-4 w-12 h-12 bg-white bg-opacity-20 rounded-full flex items-center justify-center group-hover:bg-opacity-30 transition-all duration-300 group-hover:scale-110 z-10">
            <span class="text-white font-bold transform group-hover:translate-x-1 transition-transform">→</span>
          </div>
          <div class="absolute -top-4 -right-4 w-32 h-32 border-2 border-white border-opacity-20 rounded-full group-hover:border-opacity-40 group-hover:scale-110 transition-all duration-500 z-0"></div>
        </div>
      </div>

      <!-- View More Button -->
      <div class="text-center mt-16">
        <button class="bg-red-600 hover:bg-red-700 active:bg-red-800 text-white px-10 py-4 rounded-full font-semibold text-lg tracking-wide transform transition-all duration-300 hover:scale-105 hover:shadow-lg hover:shadow-red-500/30 focus:outline-none focus:ring-4 focus:ring-red-500/50">
          View More Projects
        </button>
      </div>
    </section>

    <!-- About/CTA Section -->
    <section class="py-24 px-6 max-w-4xl mx-auto bg-[#0F0F12]">
      <div class="flex flex-col items-start">
        <h2 class="text-4xl md:text-5xl font-bold mb-4 tracking-tight text-white">À propos</h2>
        <div class="mb-12 flex items-center">
          <a href="#" class="inline-block text-2xl md:text-3xl font-bold text-[#F85430] hover:opacity-80 transition-opacity">
            Commencer un projet 
          </a>
           <!-- Diagonal arrow icon -->
          <svg class="ml-2 w-6 h-6 text-[#F85430]" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
        </div>
        <p class="text-gray-400 max-w-2xl leading-relaxed text-lg">
        </p>
      </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-gray-800 py-12 px-6 text-center">
      <div class="max-w-4xl mx-auto">
        <p class="text-gray-500 text-sm">&copy; 2025 Creative Studio. All rights reserved.</p>
      </div>
    </footer>
  </div>
</template>

<style>
@keyframes scroll-left {
  0% { 
    transform: translateX(0); 
  }
  100% { 
    transform: translateX(-50%); 
  }
}

@keyframes scroll-right {
  0% { 
    transform: translateX(-50%); 
  }
  100% { 
    transform: translateX(0); 
  }
}

.animate-scroll-left {
  animation: scroll-left 30s linear infinite;
}

.animate-scroll-right {
  animation: scroll-right 25s linear infinite;
}

/* Pause animation on hover for better user experience */
.animate-scroll-left:hover,
.animate-scroll-right:hover {
  animation-play-state: paused;
}

/* Custom styles from provided HTML */
.project-card {
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 20px 40px rgba(0,0,0,0.3);
}
/* .gradient-text { */
/*     background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); */
/*     -webkit-background-clip: text; */
/*     -webkit-text-fill-color: transparent; */
/*     background-clip: text; */
/* } */

/* Ensure base styles for body are applied if needed, though Tailwind usually handles this */
</style>