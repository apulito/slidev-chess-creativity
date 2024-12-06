---
title: WhoamI
layout: center
---

<div class="grid grid-cols-2 items-center gap-8">
  <div class="flex justify-center">
    <img src="../images/profile-pic.jpg" alt="Profile Picture" class="w-48 h-48 object-cover rounded-lg shadow-lg border-4 border-gray-300" />
  </div>

  <div>
    <h1 class="text-3xl font-bold mb-4">Chi Sono</h1>
    <p class="text-lg">Mi chiamo Alberto Pulito, sono un ingegnere informatico, scacchista da una vita.</p>
    <ul class="mt-4 text-base space-y-2">
      <li>🏅 Maestro FIDE con un picco di Elo FIDE di 2308</li>
      <li>📈 Attuale Elo: 2192</li>
      <li>🔗 Oltre 30 anni di esperienza agonistica negli scacchi</li>
    </ul>
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

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
title: photos
---

## Viaggio 

<div grid="~ cols-3 gap-6" class="mt-8 px-4">
  <img src="../images/young-pic-1.jpg" alt="Foto 1" class="w-48 h-48 object-cover rounded-lg shadow-lg mx-auto" />
  
  <img src="../images/young-pic-2.jpg" alt="Foto 2" class="w-48 h-48 object-cover rounded-lg shadow-lg mx-auto" />
  
  <img src="../images/young-pic-3.jpg" alt="Foto 3" class="w-48 h-48 object-cover rounded-lg shadow-lg mx-auto" />
  
  <img src="../images/young-pic-4.jpg" alt="Foto 4" class="w-48 h-48 object-cover rounded-lg shadow-lg mx-auto" />
  
  <img src="../images/young-pic-5.jpg" alt="Foto 5" class="w-48 h-48 object-cover rounded-lg shadow-lg mx-auto" />
  
  <img src="../images/young-pic-6.jpg" alt="Foto 6" class="w-48 h-48 object-cover rounded-lg shadow-lg mx-auto" />
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
