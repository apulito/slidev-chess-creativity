---
title: Goal
layout: center
---

## Obiettivo 
<div v-click class="text-lg mt-6 block"> Esplorare la creatività negli scacchi,  <span v-mark.circle.orange="3">un elemento essenziale </span> per vivere il gioco <span v-mark.red="4"> come un'arte appassionante </span> e continuare a studiare con piacere, nonostante la sua complessità e l'impegno richiesto.
</div>

<div v-click="5" class="mt-6 italic text-left text-base border-l-4 border-gray-400 pl-4"> 
"Alla maggior parte dei giocatori l’approccio puramente tecnico agli scacchi sembra ormai l’unica strada per accumulare punti, così la loro preparazione si basa esclusivamente su una continua ed esasperata adozione di varianti in apertura; in altre parole non sono più disposti a rinunciare al già noto per affidarsi alla propria fantasia e creatività, qualità indispensabili ad un reale e duraturo successo negli scacchi."
</div> 

<div class="w-60 relative">
  <div class="relative w-40 h-40">
    <img
      v-motion
      :initial="{ x: 800, y: -100, scale: 1.5, rotate: -50 }"
      :enter="final"
      class="absolute inset-0"
      src="https://giphy.com/embed/2oaILp6G5YA8rDVGOq"
      alt=""
    />
    <img
      v-motion
      :initial="{ y: 500, x: -100, scale: 2 }"
      :enter="final"
      class="absolute inset-0"
      src="https://sli.dev/logo-circle.png"
      alt=""
    />
    <img
      v-motion
      :initial="{ x: 600, y: 400, scale: 2, rotate: 100 }"
      :enter="final"
      class="absolute inset-0"
      src="https://sli.dev/logo-triangle.png"
      alt=""
    />
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

<!-- vue script setup scripts can be directly used in markdown, and will only affects current page -->
<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>