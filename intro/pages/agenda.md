---
layout: default
title: Agenda - Parte 1
---

# 📅 Agenda

<div class="grid grid-cols-3 gap-4 mt-12">

  <!-- Incontro 1 -->
  <div v-click="1" class="p-2 border-l-4 border-blue-400 shadow-sm rounded-md min-w-[120px]">
    <h2 class="text-sm text-blue-400">Incontro 1</h2>
    <h3 class="text-xs">L'essenza</h3>
    <p class="mt-2 text-xs">
        Esploreremo la creatività come elemento che arricchisce il gioco e come possiamo allenare il pensiero creativo.
    </p>
  </div>

  <!-- Incontro 2 -->
  <div v-click="2" class="p-2 border-l-4 border-green-400 shadow-sm rounded-md min-w-[120px]">
    <h2 class="text-sm text-green-400">Incontro 2</h2>
    <h3 class="text-xs">La Creatività nel Caos</h3>
    <p class="mt-2 text-xs">
      Scopriremo come posizioni dinamiche e complesse possano stimolare manovre fantasiose.
    </p>
  </div>

  <!-- Incontro 3 -->
  <div v-click="3" class="p-2 border-l-4 border-red-400 shadow-sm rounded-md min-w-[120px]">
    <h2 class="text-sm text-red-400">Incontro 3</h2>
    <h3 class="text-xs">L'ingegno nell'ombra</h3>
    <p class="mt-2 text-xs">
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

<div class="grid grid-cols-2 gap-4 mt-12">

  <!-- Incontro 4 -->
  <div v-click="1" class="p-2 border-l-4 border-yellow-400 shadow-sm rounded-md min-w-[120px]">
    <h2 class="text-sm text-yellow-400">Incontro 4</h2>
    <h3 class="text-xs">Flessibilità nelle strutture</h3>
    <p class="mt-2 text-xs">
      Dimostreremo come la creatività si manifesti anche nelle decisioni strategiche a lungo termine, con particolare focus sulle strutture pedonali.
    </p>
  </div>

  <!-- Incontro 5 -->
  <div v-click="2" class="p-2 border-l-4 border-purple-400 shadow-sm rounded-md min-w-[120px]">
    <h2 class="text-sm text-purple-400">Incontro 5</h2>
    <h3 class="text-xs ">Creatività vs. Intelligenza Artificiale</h3>
    <p class="mt-2 text-xs">
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