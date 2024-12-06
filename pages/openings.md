---
title: openings
---

# Aperture

<div class="flex flex-col items-center justify-start h-full space-y-10 mt-10">
  
  Ora vedremo le aperture più importanti, pronte per essere sviscerate nei minimi dettagli, siamo pronti?
  
  <div class="grid grid-cols-2 gap-12 px-8">
    <!-- Aperture del Bianco -->
    <div>
      <h2 class="text-2xl font-semibold mb-4">Bianco</h2>
      <ul class="space-y-2 text-lg">
        <li>♙ Ruy Lopez</li>
        <li>♙ Italiana</li>
        <li>♙ Gambetto di Re</li>
        <li>♙ Inglese</li>
      </ul>
    </div>
    <div>
      <h2 class="text-2xl font-semibold mb-4">Nero</h2>
      <ul class="space-y-2 text-lg">
        <li>♟️ Siciliana</li>
        <li>♟️ Francese</li>
        <li>♟️ Caro-Kann</li>
        <li>♟️ Scandinava</li>
      </ul>
    </div>
  </div>
  <div
    v-click="[1]"
    class="absolute left-1/4 top-1/2 transform -translate-y-1/2 -translate-x-1/2 w-full max-w-md h-auto"
  >
    <iframe
      src="https://giphy.com/embed/vyTnNTrs3wqQ0UIvwE"
      width="100%"
      height="250"
      frameborder="0"
      class="rounded-lg shadow-lg"
      allowfullscreen
    ></iframe>
  </div>

  <div
    v-click="[2]"
    class="absolute right-1/4 top-1/2 transform -translate-y-1/2 translate-x-1/2 w-full max-w-md h-auto"
  >
    <iframe
      src="https://giphy.com/embed/YWFmlljmSpo6k"
      width="100%"
      height="250"
      frameborder="0"
      class="rounded-lg shadow-lg"
      allowfullscreen
    ></iframe>
  </div>
  
</div>

<div class="absolute bottom-6 left-6 text-xl">
  <a href="https://github.com/apulito/slidev-chess-creativity" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
  <a href="https://albertopulito.com" target="_blank" class="slidev-icon-btn">
    <carbon:earth />
  </a>
</div>

<div @click="$slidev.nav.next" class="absolute bottom-6 right-6 text-xl py-1" hover:bg="white op-10">
  <carbon:arrow-right />
</div>
