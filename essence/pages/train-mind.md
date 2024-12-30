---
title: train-mind - parte 1
---

# 🧠 Allenamento per una solida creatività

<div class="mt-6 text-left">
    <p class="text-lg text-gray-500 mb-6">
        Allenare la creatività richiede pratiche che stimolino la mente a pensare in modo originale, a riconoscere e sfruttare pattern noti e a trovare soluzioni per affrontare le nuove sfide. Tra i metodi più efficaci troviamo:
    </p>
    <div class="grid grid-cols-2 gap-6">
        <div>
            <ul class="space-y-4">
                <li>
                    <span class="font-semibold">Analizzare alla cieca.</span>
                    <p class="mt-1 text-sm text-gray-500">
                        Perfeziona le qualità del pensiero, la memoria fotografica e la capacità di concentrazione.
                    </p>
                </li>
                <li>
                    <span class="font-semibold">Risolvere puzzle e posizioni complesse.</span>
                    <p class="mt-1 text-sm text-gray-500">
                        Aiuta a riconoscere temi ricorrenti e a comprendere come sfruttarli efficacemente per ottenere vantaggi durante la partita.
                    </p>
                </li>
            </ul>
        </div>
        <div>
            <ul class="space-y-4">
                <li>
                    <span class="font-semibold">Analisi post-mortem.</span>
                    <p class="mt-1 text-sm text-gray-500">
                        Consente di identificare gli errori e di sviluppare un approccio critico per migliorare il proprio gioco.
                    </p>
                </li>
                <li>
                    <span class="font-semibold">Lettura e ricerca.</span>
                    <p class="mt-1 text-sm text-gray-500">
                        Approfondisce ogni aspetto del gioco, stimola la curiosità e amplia la comprensione strategica e culturale degli scacchi.
                    </p>
                </li>
            </ul>
        </div>
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
title: train-mind - parte 2
---

# 🧩 Diagrammi parte 1

<div class="grid grid-cols-3 gap-4 items-center justify-center mt-12">
  <div v-click="1" v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 1 }" :leave="{ opacity: 0 }" class="flex flex-col items-center">
    <img src="../images/bogoliubov-mises.jpg" alt="Diagram 1" class="w-48 h-48 object-cover rounded-lg shadow-md border-2 border-gray-300" />
    <p class="mt-2 text-sm font-semibold">Mossa al Bianco</p>
  </div>
  <div v-click="2" v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 1 }" :leave="{ opacity: 0 }" class="flex flex-col items-center">
    <img src="../images/bird-morphy.jpg" alt="Diagram 2" class="w-48 h-48 object-cover rounded-lg shadow-md border-2 border-gray-300" />
    <p class="mt-2 text-sm font-semibold">Mossa al Nero</p>
  </div>
  <div v-click="3" v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 1 }" :leave="{ opacity: 0 }" class="flex flex-col items-center">
    <img src="../images/kramnik-ivanchuk.jpg" alt="Diagram 2" class="w-48 h-48 object-cover rounded-lg shadow-md border-2 border-gray-300" />
    <p class="mt-2 text-sm font-semibold">Mossa al Bianco</p>
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
title: train-mind - parte 3
---

# 🧩 Diagrammi parte 2

<div class="grid grid-cols-3 gap-4 items-center justify-center mt-12">
  <div v-click="1" v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 1 }" :leave="{ opacity: 0 }" class="flex flex-col items-center">
    <img src="../images/andersson-zwirs.jpg" alt="Diagram 1" class="w-48 h-48 object-cover rounded-lg shadow-md border-2 border-gray-300" />
    <p class="mt-2 text-sm font-semibold">Mossa al Bianco</p>
  </div>
  <div v-click="2" v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 1 }" :leave="{ opacity: 0 }" class="flex flex-col items-center">
    <img src="../images/ivkov-larsen.jpg" alt="Diagram 3" class="w-48 h-48 object-cover rounded-lg shadow-md border-2 border-gray-300" />
    <p class="mt-2 text-sm font-semibold">Mossa al Nero</p>
  </div>  
  <div v-click="3" v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 1 }" :leave="{ opacity: 0 }" class="flex flex-col items-center">
    <img src="../images/spragget-appel.jpg" alt="Diagram 3" class="w-48 h-48 object-cover rounded-lg shadow-md border-2 border-gray-300" />
    <p class="mt-2 text-sm font-semibold">Mossa al Bianco</p>
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
