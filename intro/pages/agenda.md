---
layout: default
title: Agenda - Parte 1
---

# 📅 Agenda

<div class="grid grid-cols-1 md:grid-cols-3 gap-4 mt-12">

  <!-- Incontro 1 -->
  <div v-click="1" class="p-4 border-l-4 border-blue-500 shadow-sm rounded-md">
    <h2 class="text-base font-bold">Incontro 1</h2>
    <h3 class="text-base">L'essenza</h3>
    <p class="mt-2 text-sm">
        Esploreremo la creatività come elemento essenziale nel gioco, partiremo dalle basi per comprendere perché il pensiero creativo sia un aspetto fondamentale e come possiamo allenarlo.
    </p>
  </div>

  <!-- Incontro 2 -->
  <div v-click="2" class="p-4 border-l-4 border-green-500 shadow-sm rounded-md">
    <h2 class="text-base font-bold">Incontro 2</h2>
    <h3 class="text-base">La Creatività nel Caos</h3>
    <p class="mt-2 text-sm">
      Scopriremo come le posizioni dinamiche e complesse possano stimolare le manovre più fantasiose.
    </p>
  </div>

  <!-- Incontro 3 -->
  <div v-click="3" class="p-4 border-l-4 border-red-500 shadow-sm rounded-md">
    <h2 class="text-base font-bold">Incontro 3</h2>
    <h3 class="text-base">L'ingegno nell'ombra</h3>
    <p class="mt-2 text-sm">
      Analizzeremo come la creatività si manifesti anche nelle strategie difensive.
    </p>
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

---
layout: default
title: Agenda - Parte 2
---

# 📅 Agenda

<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mt-8">

  <!-- Incontro 4 -->
  <div v-click="1" class="p-4 border-l-4 border-yellow-500 shadow-sm rounded-md">
    <h2 class="text-base font-bold">Incontro 4</h2>
    <h3 class="text-base">Flessibilità nelle strutture</h3>
    <p class="mt-2 text-sm">
      Dimostreremo come la creatività si manifesti anche nelle decisioni strategiche a lungo termine, con particolare focus sulle strutture pedonali.
    </p>
  </div>

  <!-- Incontro 5 -->
  <div v-click="2" class="p-4 border-l-4 border-purple-500 shadow-sm rounded-md">
    <h2 class="text-base font-bold">Incontro 5</h2>
    <h3 class="text-base">Creatività vs. Intelligenza Artificiale</h3>
    <p class="mt-2 text-sm">
      Un confronto tra la creatività umana e l'approccio dell'IA negli scacchi moderni. Come l'IA ha influenzato il gioco e cosa possiamo imparare per continuare a evolvere.
    </p>
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
