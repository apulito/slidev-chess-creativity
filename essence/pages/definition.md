---
title: Definition
---

# 🎨 Cos'è la Creatività?

<div v-click="1" class="mt-6 text-left text-gray-500">
  <p class="text-lg">
    La creatività è il <span v-mark.circle.orange="1"> cuore del gioco </span>, capace di dare vita a idee brillanti e innovative sulla scacchiera. Si manifesta nella capacità di trovare soluzioni non convenzionali, adattarsi a situazioni uniche e sviluppare nuove strategie, rendendo ogni mossa un'espressione di ingegno e originalità.
  </p>
</div>

<div v-click="2" class="grid grid-cols-2 gap-4 mt-12">
  <div class="aspect-w-16 aspect-h-9">
    <iframe
      class="rounded-lg shadow-lg"
      src="https://www.youtube.com/embed/mqlmVoOnj7o"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen
    ></iframe>
  </div>
  <div class="aspect-w-16 aspect-h-9">
    <iframe
      class="rounded-lg shadow-lg"
      src="https://www.youtube.com/embed/YWYLFQo_J9M"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
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
