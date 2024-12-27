---
title: styles
---

# ♟️ Stili di Gioco

<div class="mt-6 text-left">
    <p class="text-lg text-gray-500 mb-6">
    Gli stili di gioco possono essere suddivisi in molte categorie, ma le due principali sono 
    <span class="font-semibold text-blue-500">combinatorio</span> e 
    <span class="font-semibold text-green-500">posizionale</span>. Questi rappresentano i due macro-approcci principali al gioco, ognuno con caratteristiche uniche e interpretabili in diverse sfumature.
    </p>
</div>

<div class="grid grid-cols-2 gap-4 mt-12">
    <div class="p-4 border-l-4 border-blue-500 shadow-lg rounded-md">
        <h2 class="text-lg font-semibold text-blue-500"> Combinatorio</h2>
        <p class="mt-2 text-sm">
            Stile che si fonda sulla capacità di costruire sequenze di mosse forzate che sfruttano aspetti specifici della posizione per raggiungere obiettivi strategici o tattici.
        </p>
        <h4 class="mt-4 text-xs font-semibold">Esempi:</h4>
        <p class="text-xs">Morphy, Tal, Kasparov, Morozevich, Jobava, Dubov, Rapport.</p>
    </div>
    <div class="p-4 border-l-4 border-green-500 shadow-lg rounded-md">
        <h2 class="text-lg font-semibold text-green-500"> Posizionale</h2>
        <p class="mt-2 text-sm">
            Uno stile più solido e strategico, che si basa sulla forza delle strutture e del controllo.
        </p>
        <h4 class="mt-4 text-xs font-semibold">Esempi:</h4>
        <p class="text-xs">Capablanca, Botvinnik, Petrosjan, Karpov, Kramnik, Gelfand.</p>
    </div>

</div>

<!-- Footer -->
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
