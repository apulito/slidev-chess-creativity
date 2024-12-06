---
title: WhoamI
---

# Chi Sono

<div class="grid grid-cols-2 items-center gap-8">
  <div class="flex justify-center">
    <img src="../images/profile-pic.jpg" alt="Profile Picture" class="w-48 h-48 object-cover rounded-lg shadow-lg border-4 border-gray-300" />
  </div>
  <div>
    <p class="text-lg">Mi chiamo Alberto Pulito, sono uno scacchista da una vita. Tra una partita e l'altra, anche un po' ingegnere informatico.</p>
    <ul class="mt-4 text-base space-y-2">
      <li>🏆 Campione italiano U10, U12 e U14</li>
      <li>🏅 Campione torinese assoluto</li>
      <li>🌍 Partecipato a Mondiali, Europei ed Olimpiadi</li>
      <li>🏅 Maestro FIDE dal 2014</li>
      <li>🔗 Oltre 30 anni di esperienza agonistica negli scacchi</li>
    </ul>
  </div>
</div>

<!-- Links on the left -->
<div class="absolute bottom-6 left-6 text-xl">
  <a href="https://github.com/apulito/slidev-chess-creativity" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
  <a href="https://albertopulito.com" target="_blank" class="slidev-icon-btn">
    <carbon:earth />
  </a>
</div>

<!-- navigation on the right -->
<div @click="$slidev.nav.next" class="absolute bottom-6 right-6 text-xl py-1" hover:bg="white op-10">
  <carbon:arrow-right />
</div>